# Business Card Implementation Notes

## CSS Selector Issue Resolution

### Problem
QR positioning for bleed mode wasn't working - `right: 100px !important` was being ignored.

### Root Cause
Incorrect CSS selector: `body.with-bleed .single-sided .qr-container`
This selector was looking for an element with class `single-sided` *inside* the body, but both classes are on the body element itself.

### Solution
Corrected selector to: `body.with-bleed.single-sided .qr-container`
(Note: no space between `.with-bleed` and `.single-sided`)

## Current QR Positioning Values

```css
/* Base positioning */
.qr-container {
    position: absolute;
    bottom: 22px;
    right: 8px;
}

/* Single-sided card without bleed */
.single-sided .qr-container {
    top: 28px;
    right: 14px;
    bottom: auto;
}

/* Single-sided card with bleed */
body.with-bleed.single-sided .qr-container {
    top: 8px !important;
    right: 100px !important;  /* User testing this value */
}
```

## HTML Structure
```html
<body class="single-sided">  <!-- Default -->
<body class="single-sided with-bleed">  <!-- When bleed enabled -->
    <div class="card-container">
        <div class="window">
            <div class="window-body">
                <div class="qr-container">
                    <!-- QR code here -->
                </div>
            </div>
        </div>
    </div>
</body>
```

## Bleed Implementation
- Standard card: 3.5" x 2"
- With bleed: 3.75" x 2.25" (0.125" bleed on all sides)
- Window centering in bleed mode uses flexbox
- Background color extends to bleed edges

## Testing Notes
- User is actively adjusting QR positioning for bleed mode
- The `!important` flags are necessary due to CSS specificity conflicts
- Browser dev tools essential for debugging selector issues