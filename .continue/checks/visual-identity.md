---
name: Visual Identity
description: Enforce the visual language — blueprint blue, terminal green, warm amber on dark charcoal
---

r/factorymustgrow's visual identity sits at the intersection of Factorio's isometric blueprint aesthetic and the terminal/IDE dark-mode world that software engineers live in. It should feel like a factory control room — dark backgrounds, precise color coding, information-dense layouts.

The canonical color palette:

- **Blueprint blue (#3B82F6) + Indigo (#6366F1)** — Primary. Used for structural elements, links, headers, blueprint-style content.
- **Terminal green (#22C55E)** — Throughput, success, active production, "systems nominal."
- **Warm amber (#F59E0B)** — Alerts, bottlenecks, human attention needed, warnings.
- **Dark charcoal (#1E1E2E)** — Backgrounds. The control room is dark.
- **White/light gray** — Text, secondary elements.

The visual standards:

1. **Dark backgrounds are default.** Light mode is not the factory aesthetic. Dark charcoal backgrounds with high-contrast text and color-coded accents.
2. **Color codes carry meaning.** Blue is structure, green is healthy throughput, amber is attention needed. Don't use colors decoratively — they're status indicators.
3. **Isometric meets terminal.** The visual sweet spot is Factorio's isometric grid overlaid with terminal/monospace typography. Blueprint paper textures, grid lines, monospace fonts.
4. **No corporate stock imagery.** No generic tech visuals, no stock photos of people looking at screens. Diagrams, blueprints, terminal output, factory screenshots — real artifacts from real builds.
5. **Information density is a feature.** Factory control rooms show a lot of data. Sparse, minimalist design is off-brand. Dense, well-organized information displays are on-brand.

Flag as failing if:

- Light/white backgrounds used as primary (not the factory aesthetic)
- Colors used decoratively without status meaning
- Corporate stock photography or generic tech imagery
- Visual style that could belong to any subreddit (no factory identity)
- Sparse, minimalist layouts that waste space a factory dashboard would fill

Do NOT flag:

- Slight variations in exact hex values (the palette is a guide, not a spec sheet)
- User-submitted content that doesn't match the palette (the identity applies to sub infrastructure, not user posts)
- Screenshots of actual Factorio gameplay or actual terminal output (real artifacts are always on-brand)
- Dark mode variations (different charcoal shades are fine)
