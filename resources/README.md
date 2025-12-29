# Design Resources Library

Curated design resources organized by category for quick reference during web projects.

## Directory Structure

```
resources/
├── fonts/           # Typography resources
│   └── index.md     # Font libraries, pairing tools, typography guides
├── colors/          # Color tools and palettes
│   └── index.md     # Color generators, palette tools, accessibility checkers
├── icons/           # Icon libraries
│   ├── index.md     # SVG icon libraries, icon packs
│   └── icon-fonts.md # Icon font resources
├── images/          # Visual assets
│   ├── stock-photos.md    # Stock photography
│   ├── stock-videos.md    # Video resources
│   ├── vectors-clip-art.md # Vector graphics
│   ├── logos.md           # Logo resources
│   ├── mockups.md         # Product mockups
│   ├── ui-graphics.md     # UI elements
│   └── favicons.md        # Favicon generators
├── layout/          # Layout and CSS
│   ├── css-frameworks.md    # Tailwind, Bootstrap, etc.
│   ├── css-methodologies.md # BEM, SMACSS, etc.
│   └── templates.md         # HTML/CSS templates
├── motion/          # Animation resources
│   ├── css-animations.md        # CSS animation libraries
│   └── js-animation-libraries.md # JS animation (Framer, GSAP)
├── components/      # UI component libraries
│   ├── react-ui.md        # React libraries
│   ├── vue-ui.md          # Vue libraries
│   ├── svelte-ui.md       # Svelte libraries
│   ├── angular-ui.md      # Angular libraries
│   ├── react-native-ui.md # React Native libraries
│   └── kits.md            # Multi-framework kits
├── media/           # Audio/Video resources
│   └── audio.md     # Stock music, sound effects
├── tools/           # Design tools
│   ├── online-tools.md   # Browser-based tools
│   ├── software.md       # Downloadable software
│   └── chart-libraries.md # Data visualization
└── inspiration/     # Design references
    ├── index.md           # Design inspiration sites
    └── design-systems.md  # Style guides, design systems
```

## Usage

### During Design Phase
1. **Font Selection**: Start with `fonts/index.md` for typography resources
2. **Color Palette**: Use `colors/index.md` for palette generators
3. **Icons**: Check `icons/index.md` for icon libraries
4. **Layout**: Reference `layout/css-frameworks.md` for CSS frameworks

### Component Selection
- Match framework to project: `components/react-ui.md`, `components/vue-ui.md`, etc.
- For multi-framework: `components/kits.md`

### Animation
- CSS-first: `motion/css-animations.md`
- Complex animations: `motion/js-animation-libraries.md`

## Integration with PAI

These resources are consumed by:
- `design-system` skill (orchestrator)
- `design-planning` skill (Phase 1.5)
- `theme-factory` skill (pre-set themes)

Decision frameworks at `~/.claude/library/design/decision-frameworks/` reference these resources.

---

*Last updated: 2025-12-11*
