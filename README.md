# Awesome Claude Design Brand Creative System

A collection and working framework for `DESIGN.md` files that go beyond UI tokens.

This fork expands the original `DESIGN.md` idea into a fuller **brand creative system**: color, typography, layout, components, photography, imagery, motion, social creative, website usage, and agent-facing production rules in one markdown file.

The goal is simple: give Claude Design, Claude Code, Codex, Cursor, Stitch, or any design-capable agent enough direction to make digital creative that feels like a coherent brand system, not a generic landing page with matching colors.

## Why This Fork Exists

Most AI-readable design docs focus on interface scaffolding:

- color tokens
- type scale
- buttons and cards
- spacing and layout
- responsive behavior

That is useful, but brand work usually needs more. A usable creative system also answers questions like:

- What kind of photography belongs in the brand?
- How should images be cropped, graded, layered, or paired with type?
- What should social ads feel like compared with website heroes?
- When should the system use product photography, lifestyle imagery, editorial imagery, screenshots, illustration, or abstract visuals?
- What makes a generated asset feel on-brand instead of merely "nice"?

This repo treats those answers as part of the design system.

## What Is A Brand Creative `DESIGN.md`?

A brand creative `DESIGN.md` is a single markdown file that describes a brand's visual and creative language in a format an AI agent can act on.

It should be specific enough to guide production decisions, but flexible enough to create new pages, ads, carousels, thumbnails, decks, and product moments without needing a human art director to restate the same rules every time.

| File | Who Reads It | What It Defines |
|---|---|---|
| `AGENTS.md` | Coding agents | How to work in the codebase |
| `DESIGN.md` | Design agents | How the product interface should look and behave |
| Brand creative `DESIGN.md` | Design and creative agents | How the brand should show up across UI, web, social, ads, imagery, and motion |

## Core Template

Start here:

- [Brand Creative System Template](templates/BRAND_CREATIVE_SYSTEM.md)

The template includes 14 sections:

| # | Section | What The Agent Uses It For |
|---|---|---|
| 1 | Brand Position & Creative Thesis | The unifying point of view |
| 2 | Visual Theme & Atmosphere | Mood, density, energy, and restraint |
| 3 | Color Palette & Roles | Semantic color usage and creative behavior |
| 4 | Typography Rules | Type hierarchy, rhythm, and expressive limits |
| 5 | Layout Principles | Composition, spacing, grids, and pacing |
| 6 | Component Styling | Interface primitives and interaction states |
| 7 | Photography & Imagery System | Subject matter, composition, lighting, realism, and image treatment |
| 8 | Social Creative System | Paid social, organic, carousels, stories, thumbnails |
| 9 | Website Creative System | Heroes, product sections, editorials, proof, galleries |
| 10 | Motion & Interaction | Transitions, reveals, scroll behavior, motion mood |
| 11 | Voice In Visual Context | How copy and visuals work together |
| 12 | Do / Don't Rules | Guardrails for keeping outputs on-system |
| 13 | Quality Bar & Review Checklist | Criteria for judging finished creative |
| 14 | Agent Prompt Guide | Reusable instructions for future work |

## Example Systems

These are educational, unofficial, public-pattern-inspired examples. They are not official brand guidelines.

- [Nike-Inspired Performance Creative System](examples/nike-inspired-creative-system.md)
- [Airbnb-Inspired Hospitality Creative System](examples/airbnb-inspired-creative-system.md)
- [Apple-Inspired Product Creative System](examples/apple-inspired-creative-system.md)

Use them to see how photography and imagery can be defined as part of the system rather than bolted on later.

## Guides

- [Creative System Checklist](guides/creative-system-checklist.md)

The checklist is meant for reviewing a `DESIGN.md` before handing it to an agent.

## How To Use This Repo

1. Pick the template or an example closest to the brand direction you want.
2. Replace the example language with your brand's actual audience, product, offer, and creative standards.
3. Attach the file to Claude Design, Claude Code, Codex, Cursor, Stitch, or another design-capable agent.
4. Ask the agent to create a design system, web page, ad concept, carousel, deck, or creative asset from the file.
5. Review the output against the checklist, then tighten the doc where the agent made weak assumptions.

Example prompt:

```text
Create a landing page and three paid social static ad concepts using this brand creative DESIGN.md. Treat the photography, layout, social creative, and do/don't sections as binding art direction.
```

## Relationship To The Original Repo

This repo began as a fork of [VoltAgent/awesome-claude-design](https://github.com/VoltAgent/awesome-claude-design), which collects ready-to-use `DESIGN.md` inspirations for Claude Design.

The original repo is focused on fast UI scaffolding from brand-inspired design docs. This fork keeps that spirit, but expands the format toward digital brand creative: websites, social media, ads, editorial modules, product storytelling, and photography direction.

## Suggested Future Additions

- Add more fully developed example systems for photography-led brands.
- Convert original `DESIGN.md` entries into the expanded 14-section format.
- Add a simple rubric for scoring agent outputs.
- Add before/after examples showing the difference between UI-only and brand-creative docs.
- Add category-specific templates for SaaS, consumer products, creator brands, local services, healthcare, fashion, food, and ecommerce.

## License & Disclaimer

This repository is MIT licensed; see [LICENSE](LICENSE).

Example systems in this repo are educational starting points inspired by publicly observable design patterns. They are not official design systems and are not affiliated with, endorsed by, or sponsored by the companies named. All trademarks, brand names, logos, and proprietary typefaces belong to their respective owners.

Use these docs as inspiration for original systems, not as instructions to impersonate protected brands.
