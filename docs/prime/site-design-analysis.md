# evangelista.moe Design Analysis

## 3-Second Test Results

**What visitors learn immediately:**
1. ❌ "Display Properties" window (confusing - is this a Windows tutorial?)
2. ✅ Name "Marc Evangelista" (but buried in second window)
3. ❌ Theme switcher (dominates but adds no hiring value)

**First Impression:** Feels like a Windows theme demo, not a developer portfolio

## Immediate Impact Fixes (10 minutes)

1. **Hero Statement Above Everything**
   - "I made C++ database builds 60x faster at Bloomberg"
   - Subtext: "AI engineer. make computer do work."
   - This INSTANTLY differentiates you

2. **Minimize Theme Switcher**
   - Move to corner as small toggle or menu item
   - It's fun but shouldn't be the first thing seen

3. **Consolidate Windows**
   - One main window with clear hierarchy
   - Sidebar for supplementary info only

## Structural Improvements

### Current Problems:
- Information scattered across too many windows
- Most impressive credential (60x) hidden in tabs
- No clear visual flow
- Theme novelty overshadows substance

### Recommended Structure:

```
HERO SECTION (No window, just text)
├── "I made C++ database builds 60x faster"
├── "AI engineer. make computer do work."
└── "real human since 1990s"

MAIN WINDOW (Projects/Work)
├── Current Projects (visible immediately)
├── Quick proof points
└── Interactive elements

SIDEBAR (Personal touches)
├── Stats/quirks
├── Contact
└── Theme toggle (small)
```

## Personality Amplifiers

### Keep These (They Work):
- "make computer do work" - perfect tone
- "real human since 1990s" - differentiating
- ADHD superpower framing
- Interactive table rows with alerts

### Add These:
1. **Keyboard Navigation**
   - Alt+1/2/3 for tabs (shows you're technical)
   - Konami code for easter egg

2. **Performance Counter**
   - Live updating "optimizations today: X"
   - References your optimization expertise

3. **Console Message**
   ```javascript
   console.log("Yep, I checked the console too. Let's talk: marc@evangelista.moe");
   ```

## Technical Polish

### Performance:
- Both CSS libraries loading (pick one per page or lazy load)
- No critical CSS - inline essential styles

### Mobile:
- Windows metaphor breaks on small screens
- Need simpler mobile layout
- Touch targets too small

### Accessibility:
- Good: Semantic HTML, ARIA labels
- Missing: Skip links, focus indicators
- Theme switcher needs keyboard support

## Visual Hierarchy Fixes

### Current Hierarchy (Wrong):
1. Theme switcher
2. Window chrome
3. Tabs
4. Actual content

### Correct Hierarchy:
1. **Your differentiator** (60x faster)
2. **What you do** (AI engineer)
3. **Current work** (projects)
4. **Personality** (human touches)
5. **Actions** (contact/resume)

## Component Usage Recommendations

### Keep:
- **Tabs** - Good for organizing projects/experience
- **Progress bars** - Visual way to show optimization
- **Tree view** - IF you add more project details
- **Status bar** - Fun touch at bottom

### Remove/Minimize:
- **Multiple windows** - One main window max
- **Theme switcher prominence** - Make it subtle
- **Sidebar on mobile** - Stack vertically instead

### Add:
- **Dropdown** for "How I optimize" examples
- **Text input** that auto-completes your skills
- **Buttons with icons** for main CTAs

## Final Recommendations

### The One Change That Matters Most:
**Put "I made C++ database builds 60x faster at Bloomberg" as the first thing people see, outside any window, in large text.**

This single change transforms you from "another AI engineer" to "the engineer who makes things 60x faster."

### The Experience Flow:
1. They see the 60x claim (wow)
2. They see current AI work (relevant)
3. They notice the Windows theme (memorable)
4. They explore and find personality touches (human)
5. They contact you (hired)

### Mobile Approach:
- Drop the Windows metaphor on mobile
- Simple stack with same content hierarchy
- Maybe just terminal aesthetic with green text

Remember: The Windows theme should be the cherry on top, not the whole sundae. Your results and humanity are what get you hired.