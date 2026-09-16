# Visual Style Skills

Reusable AI skills for refined visual design, UI/UX, branding, editorial design, and image generation.

This repository contains two versions of one visual language: **minimal, restrained, quiet, rational, precise, modern, and editorial**.

## Skills

### `visual-style`

The full system. Use it when the task needs deliberate art direction and detailed control over hierarchy, composition, spacing, typography, color, imagery, material, motion, and final polish.

Best for:

- product and UI/UX design
- websites, landing pages, dashboards, and applications
- brand identity and visual systems
- posters, covers, editorial layouts, reports, and presentations
- image-generation art direction
- visual critique, redesign, and refinement

### `visual-style-lite`

A compact version of the same aesthetic. It keeps the strongest defaults and removes most explanation and secondary rules.

Best for:

- small or fast design tasks
- limited-context agents
- lightweight system prompts
- quick visual refinement while keeping consistent taste

## Difference

| | `visual-style` | `visual-style-lite` |
|---|---|---|
| Core aesthetic | Same | Same |
| Detail | Full visual system | Condensed essentials |
| Best for | Complex / high-fidelity work | Fast / small tasks |
| Coverage | Layout, type, color, imagery, material, motion, QA | Composition, hierarchy, type, color, restraint |

## Usage

Copy the desired `SKILL.md` into your AI agent or skill system, then invoke it for a visual task.

Full version example:

```text
Use the visual-style skill to redesign this dashboard.
Keep all functionality unchanged, but improve hierarchy, spacing,
typography, density, consistency, and visual coherence.
```

Lite version example:

```text
Use visual-style-lite to refine this login page.
Make it quiet, precise, modern, and editorial.
```

Image direction example:

```text
Use visual-style to art-direct this image.
Remove decorative noise, simplify the composition, strengthen the focal point,
and keep the result restrained, premium, and timeless.
```

## Structure

```text
README.md
skills/
  visual-style/
    SKILL.md
  visual-style-lite/
    SKILL.md
```

## Design intent

The system deliberately avoids decorative excess, generic gradient-heavy “AI style”, noisy glass effects, arbitrary card nesting, oversized radii, weak hierarchy, visual clutter, and novelty without purpose.

The goal is not to make every design look identical. The goal is to make every visual decision feel **intentional, coherent, calm, and exact**.
