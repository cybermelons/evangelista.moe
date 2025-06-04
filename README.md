# evangelista.moe

Personal portfolio site with Windows 98/XP aesthetic. Real human engineer who makes computers do work.

## Design Philosophy

**THE WINDOWS AESTHETIC IS THE POINT.** The theme switcher between Windows 98 and XP is a core feature, not a gimmick. This site is meant to:

1. Show I'm a real programmer who grew up with actual computers
2. Stand out from generic developer portfolios
3. Work perfectly on mobile WITH the Windows UI (windows stack vertically)
4. Be fun and memorable

## Key Features

- **Theme Switcher**: Toggle between Windows 98 and XP styles
- **Multiple Windows**: Each section in its own window (Display Properties, Main Content, Quick Info, Sticky Note)
- **Interactive Elements**: 
  - Clickable table rows with alerts
  - Productivity mode toggle (Hyperfocus vs Squirrel!)
  - Tree view for projects
  - Progress bar showing 60x optimization
- **Easter Eggs**:
  - Console message for developers
  - Konami code achievement
  - Alt+1/2/3/4 keyboard navigation for tabs

## Content Strategy

- Lead with personality: "AI engineer. make computer do work."
- Show concrete achievement: 60x faster C++ builds at Bloomberg
- Keep it human: ADHD as superpower, "real 90s baby"
- Humor touches: Sticky note with "humor lower human guard"

## Technical Stack

- Astro (static site generation)
- 98.css and XP.css libraries
- Vanilla JavaScript for interactivity
- No build complexity, just ship

## Important Note

**DO NOT** remove the Windows aesthetic or "simplify" to a minimal design. The whole point is the nostalgic, fully-functional Windows UI that works everywhere. If someone suggests making it "cleaner" or "more modern" - they don't get it.

The site should feel like you're browsing someone's Windows desktop from 2001, because that's when real programmers were made.

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `pnpm install`             | Installs dependencies                            |
| `pnpm dev`             | Starts local dev server at `localhost:4321`      |
| `pnpm build`           | Build your production site to `./dist/`          |
| `pnpm preview`         | Preview your build locally, before deploying     |
| `pnpm astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `pnpm astro -- --help` | Get help using the Astro CLI                     |

## Local Development

```bash
cd evangelista.moe
pnpm install
pnpm dev
```

## Deployment

Site deploys to evangelista.moe via [deployment service].

---

Remember: This is a 3-hour project that shows more personality than a 3-week "professional" portfolio. Ship weird things that actually work.

## Future Concept: Neon Genesis Evangelista (NGE)

An alternative theme concept that transforms the portfolio from "quirky developer" to "consciousness engineer":

### Core Concept
- **Visual**: Stark black/white Evangelion-inspired terminal aesthetics with compressed typography
- **Narrative**: Position as "PILOT-01" who actively operates their mind-body system rather than drifting
- **Philosophy**: "Most people sleepwalk through life" - apply technical rigor to consciousness development

### Key Elements
- Compressed serif headers (Crimson Text with CSS transform)
- Terminal/HUD interfaces with green-tinted displays  
- Progress bars showing "97.3% synchronization" (always improving, never complete)
- Glitch effects suggesting system evolution
- 5-act narrative structure from initialization to ongoing mission

### Connection to Projects
- **Lilaya**: The practical application of consciousness engineering
- **tiddy.city**: Becomes the "tactical map" for navigating inner world via NUT system
- **evangelista.moe**: Bridges technical achievements with consciousness work

This concept elevates the brand from Windows nostalgia to Eva-inspired "pilot your own life" framework, connecting all projects under systematic self-development. See `/nge/nge.md` for full design system.