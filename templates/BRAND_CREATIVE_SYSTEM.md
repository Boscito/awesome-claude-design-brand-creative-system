# Brand Creative System `DESIGN.md`

Use this template to define a brand system that can guide websites, social creative, ads, decks, product storytelling, and UI scaffolds.

Replace bracketed guidance with brand-specific rules. Keep the language concrete. Agents need decisions, not vibes.

## 1. Brand Position & Creative Thesis

### Brand Role
[What the brand helps people do, feel, understand, or become.]

### Audience
[Primary audience, emotional state, sophistication level, objections, and what they need to believe.]

### Creative Thesis
[One sentence that explains the creative point of view. Example: "Make technical capability feel calm, human, and immediately usable."]

### Brand Tension
[The two forces the brand balances. Example: "premium but warm", "technical but playful", "fast but trustworthy".]

## 2. Visual Theme & Atmosphere

### Overall Feel
[3-6 grounded adjectives with explanation.]

### Energy Level
[Quiet, high-energy, editorial, cinematic, utilitarian, luxurious, playful, etc.]

### Density
[Sparse, moderate, information-rich, campaign-style, dashboard-dense.]

### Signature Moves
[Repeatable visual behaviors: full-bleed photos, large type over image, split proof modules, product closeups, tactile shadows, editorial grids.]

## 3. Color Palette & Roles

### Core Colors

| Token | Hex | Role |
|---|---|---|
| `--color-background` | `#000000` | [Primary canvas role] |
| `--color-surface` | `#111111` | [Cards, panels, or image mats] |
| `--color-text` | `#ffffff` | [Primary text] |
| `--color-muted` | `#9a9a9a` | [Secondary text] |
| `--color-accent` | `#ff5a1f` | [Calls to action, key highlights] |

### Color Behavior
[How color should be used: restrained, immersive, functional, emotional, editorial, seasonal, etc.]

### Image + Color Relationship
[How photography interacts with color: warm grade, neutral whites, high contrast, muted color, accent overlays, colored backdrops.]

## 4. Typography Rules

### Type Personality
[What typography should communicate.]

### Recommended Fonts
[Primary, secondary, mono, display, and fallback guidance.]

### Hierarchy

| Level | Usage | Behavior |
|---|---|---|
| Display | Hero headlines, campaign statements | [Scale, weight, casing, tracking] |
| H1-H3 | Page and section hierarchy | [Rhythm and contrast] |
| Body | Explanatory copy | [Readability rules] |
| Caption | Metadata, labels, proof points | [Density and tone] |

### Type Over Images
[Rules for contrast, placement, scrims, alignment, and when not to place text over imagery.]

## 5. Layout Principles

### Composition
[Grid, asymmetry, centered layouts, editorial flow, product-first hierarchy.]

### Spacing
[Breathing room, compactness, rhythm, section pacing.]

### Cropping & Framing
[How layout crops photos, product shots, screenshots, portraits, and lifestyle images.]

### Responsive Behavior
[How the system changes on mobile, tablet, and desktop.]

## 6. Component Styling

### Buttons
[Shape, size, contrast, states, icon usage, CTA hierarchy.]

### Cards
[When cards are allowed, how media is handled, border radius, shadows, borders.]

### Navigation
[Density, labels, transparency, sticky behavior, mobile collapse.]

### Forms & Inputs
[Tone, affordance, validation, error states.]

### Data / Proof Modules
[Metrics, testimonials, quotes, press, charts, logos, social proof.]

## 7. Photography & Imagery System

### Imagery Role
[What imagery does for the brand: proof, aspiration, instruction, emotion, scale, clarity, trust.]

### Subject Matter
[People, product, environments, hands, interiors, landscapes, UI, objects, textures, moments.]

### Photography Style
[Documentary, premium studio, natural lifestyle, editorial, cinematic, UGC-like, clinical, macro, high-speed, behind-the-scenes.]

### Composition Rules
[Negative space, full-bleed, centered subjects, off-axis subjects, close crops, environmental context, eye-line, depth.]

### Lighting
[Natural daylight, hard flash, soft studio, low-key, high-key, golden hour, practical lights, screen glow.]

### Color Treatment
[Warm/cool grade, saturation, contrast, grain, black-and-white, muted palettes, skin tone handling.]

### Product Imagery
[How the product is shown: in use, isolated, macro, scale reference, packaging, detail, before/after.]

### People Imagery
[Casting, expression, styling, posture, authenticity, diversity, relationship to product.]

### Illustration / Iconography / Abstract Visuals
[When to use non-photo visuals and how they should behave.]

### Image Quality Bar
[What makes an image acceptable or unacceptable.]

## 8. Social Creative System

### Paid Social
[Rules for static ads, hooks, visual hierarchy, product visibility, offer placement, proof, disclaimers.]

### Organic Social
[Rules for community, education, launches, behind-the-scenes, editorial rhythm.]

### Carousels
[Cover slide, sequence logic, pacing, image-to-text ratio, final CTA.]

### Stories / Reels / Shorts Thumbnails
[Safe zones, vertical crops, face/product scale, caption placement.]

### Platform Behavior
[How the system changes for Instagram, TikTok, Facebook, LinkedIn, X, Pinterest, YouTube.]

## 9. Website Creative System

### Hero Sections
[Photo/video/product usage, headline placement, CTA hierarchy, trust signals.]

### Product Sections
[How to show benefits, features, comparisons, proof, screenshots, product photography.]

### Editorial Sections
[How to tell stories, use pull quotes, sidebars, timelines, behind-the-scenes.]

### Conversion Sections
[Offer modules, testimonials, FAQs, pricing, signup, guarantees.]

### Galleries
[Image rhythm, captions, masonry/grid behavior, lightbox or no lightbox.]

## 10. Motion & Interaction

### Motion Mood
[Fast, subtle, cinematic, playful, restrained, tactile.]

### Interaction Rules
[Hover, press, reveal, scroll, page transition, carousel behavior.]

### Media Motion
[Video loops, cinemagraphs, parallax, product rotation, animated screenshots.]

## 11. Voice In Visual Context

### Copy + Visual Relationship
[Does copy explain, provoke, reassure, label, sell, or narrate?]

### Headline Style
[Short, declarative, poetic, technical, benefit-led, editorial.]

### Caption Style
[How captions support imagery without over-explaining.]

## 12. Do / Don't Rules

### Do

- [Concrete rule]
- [Concrete rule]
- [Concrete rule]

### Don't

- [Concrete anti-pattern]
- [Concrete anti-pattern]
- [Concrete anti-pattern]

## 13. Quality Bar & Review Checklist

Before finalizing creative, verify:

- The first visual signal matches the brand thesis.
- Photography and imagery follow the stated subject, composition, lighting, and treatment rules.
- Type hierarchy is clear at mobile and desktop sizes.
- Color is used according to role, not decoration.
- Social assets can be understood in under two seconds.
- Website assets have enough detail and proof to support conversion.
- The result does not feel like a generic SaaS, generic luxury, or generic AI-generated layout.

## 14. Agent Prompt Guide

When using this file with an agent, say:

```text
Use this brand creative DESIGN.md as binding art direction. Produce work that follows the visual system, photography rules, social creative rules, website rules, and quality checklist. If a requested asset conflicts with the system, preserve the system and explain the tradeoff.
```

For social creative:

```text
Create three paid social static concepts from this DESIGN.md. Each concept should include layout direction, photography direction, headline, supporting copy, CTA, and rationale.
```

For websites:

```text
Create a responsive landing page from this DESIGN.md. Use the photography and imagery system to decide hero media, product sections, proof modules, and conversion moments.
```
