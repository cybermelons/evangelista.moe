# Working Plan - evangelista.moe

## Project Overview

Simple portfolio site with terminal aesthetic. Shows Marc as an AI engineer who ships real products. No philosophy, just evidence of technical competence.

### Core Identity

- **Tagline**: "Terminal enthusiast who ships AI-powered tools"
- **Tone**: Technical but personable, concrete examples, slight weirdness
- **Visual Identity**: Terminal aesthetic (monospace, green/amber on black)

## Design Direction

### Visual Style
- **Color Scheme**: Black background, green primary text, amber accents
- **Typography**: Monospace font throughout (Fira Code, JetBrains Mono, or similar)
- **Layout**: Single page, vertical scroll, minimal sections
- **Effects**: Blinking cursor, subtle typing animations, terminal-style transitions




## Site Structure (Single Page)

```
Marc Evangelista
---------------
> Terminal enthusiast who ships AI-powered tools

Current projects:
• Lilaya - Game where daily thoughts/urges/tasks build virtual kingdoms
• Music Practice Tracker - Visualizes practice patterns, finds what works
• Claude Workflows - Custom agents for code generation and doc processing

Previous work:
• Bloomberg - Made C++ database builds 60x faster (10+ hrs/day saved)
• Toki - Built Ethereum loyalty rewards for Shopify stores

I ship weird things that actually work. ADHD is my superpower.

marc@evangelista.moe
github.com/cybermelon

[GitHub] [LinkedIn] [Resume PDF]
```

## Technical Implementation

### Stack
- **Framework**: Astro (static site generation)
- **Package Manager**: pnpm
- **Styling**: Plain CSS with terminal theme
- **Animations**: CSS only (typing effect, blinking cursor)
- **Deployment**: Vercel/Netlify

### Terminal Effects
- Blinking cursor after headings
- Typing animation on load (optional)
- Green glow on links
- Amber highlights for CTAs
- ASCII art elements (subtle)

## Copy Guidelines

### Voice Characteristics
- Technical and direct
- No fluff or philosophy
- Show, don't tell
- Terminal-style formatting where appropriate

### Key Messages
1. **I build with AI**
2. **I ship real products**
3. **I have technical depth**
4. **ADHD is a feature, not a bug**

## Development Plan

### Phase 1: Setup (30 min)
- [ ] Initialize Astro project with pnpm
- [ ] Create single index page
- [ ] Set up terminal CSS theme
- [ ] Add monospace font

### Phase 2: Implementation (2 hours)
- [ ] Add all content to single page
- [ ] Style terminal effects
- [ ] Make responsive
- [ ] Add links

### Phase 3: Deploy (30 min)
- [ ] Test locally
- [ ] Deploy to Vercel/Netlify
- [ ] Test live site

## Notes

- Keep it simple - this is a 3-hour project max
- Terminal theme makes it memorable
- Content > Design
- Ship it, don't perfect it

## Full Copy Content

```
Marc Evangelista
---------------
> Terminal enthusiast who ships AI-powered tools

Current projects:
• Lilaya - Game where daily thoughts/urges/tasks build virtual kingdoms
• Music Practice Tracker - Visualizes practice patterns, finds what works
• Claude Workflows - Custom agents for code generation and doc processing

Previous work:
• Bloomberg - Made C++ database builds 60x faster (10+ hrs/day saved)
• Toki - Built Ethereum loyalty rewards for Shopify stores

I ship weird things that actually work. ADHD is my superpower.

marc@evangelista.moe
github.com/cybermelon

[GitHub] [LinkedIn] [Resume PDF]
```

## CSS Styling Guide

```css
:root {
  --bg: #000000;
  --text: #00ff00;
  --accent: #ffa500;
  --dim: #008800;
}

body {
  background: var(--bg);
  color: var(--text);
  font-family: 'Fira Code', monospace;
  padding: 2rem;
  max-width: 80ch;
  margin: 0 auto;
}

a {
  color: var(--accent);
  text-decoration: none;
}

a:hover {
  text-shadow: 0 0 5px var(--accent);
}

/* Blinking cursor */
.cursor::after {
  content: '_';
  animation: blink 1s infinite;
}

@keyframes blink {
  0%, 50% { opacity: 1; }
  51%, 100% { opacity: 0; }
}
```

---
Last Updated: 2025-01-30
