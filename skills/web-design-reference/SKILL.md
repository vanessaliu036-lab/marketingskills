---
name: web-design-reference
description: "Research-first web/UI design skill for premium landing pages, hero sections, product pages, dashboards, interactive components, motion, hover/focus effects, maps, text effects, and visual polish. Use when the user asks to design, redesign, improve, or implement a website/UI and wants stronger references instead of generic AI styling. Grounds decisions in curated sources such as Refero Styles, Scrolltide, Minimal Gallery, Kage, shadcn/ui, Aceternity UI, Magic UI, Motion Primitives, Uiverse, UIAble, mapcn, MicroKit UI, Kinetics, Liquid Glass, and CSS Text Effects. Preserve the user's brand system, synthesize references rather than cloning, and route implementation to the relevant framework/motion skill only after the visual direction is locked."
metadata:
  version: "1.0.0"
  category: web-design
  owner: Vanessa
---

# Web Design Reference

## Purpose

Use this skill to prevent generic AI-made website design.

The job is not to browse a gallery and copy a page. The job is to:

1. understand the product and brand,
2. research strong references,
3. choose a dominant visual direction,
4. borrow only bounded details from secondary sources,
5. turn the reference logic into a precise implementation brief,
6. build or hand off code without losing the chosen visual identity,
7. validate the rendered result against the reference lock.

Project or brand-specific rules always override a reference.

If a brand kit, design token file, existing site, approved screenshot, or prior design direction exists, read it first.

---

# 1. Trigger Conditions

Use this skill when the user asks for:

- website or landing-page design
- homepage / hero redesign
- premium or editorial web styling
- UI polish
- motion-heavy or scroll-driven websites
- hover, pointer, focus-reveal, spotlight, glass, or shader-like effects
- component inspiration
- map UI
- text animation or text effects
- visual direction for React / Next.js / Tailwind work
- "make this less AI-looking"
- "make this more premium"
- "find a better reference"
- "use this screenshot/style but adapt it to my brand"

Do not use it for a purely backend, API, deployment, SEO, analytics, or data task unless a visual interface is part of the requested output.

---

# 2. Non-Negotiable Rules

## Research before design

Do not invent a design direction from generic model taste when strong references can be researched.

Before implementation, identify a small set of references and lock one dominant direction.

## Brand beats reference

Never overwrite the user's existing:

- brand colors
- typography rules
- logo rules
- photography rules
- product truth
- content hierarchy
- accessibility requirements
- technical constraints

A reference contributes design logic, not brand ownership.

## Synthesize, do not clone

Never reproduce a complete third-party page, paid prompt, paid component, or proprietary asset.

Do not copy:

- premium prompt text verbatim
- paid template source
- proprietary imagery
- complete visual compositions that are recognizably identical

Instead extract:

- composition logic
- spacing
- hierarchy
- type scale
- interaction pattern
- movement model
- surface treatment
- component behavior

Then adapt them to the user's own product and brand.

## No reference averaging

If three references are stylistically different, do not blend them into a generic midpoint.

Choose:

- one primary reference for canvas, composition, rhythm and type
- one secondary reference for a specific component or interaction
- optionally one second secondary reference for another narrow detail

## Avoid default AI styling

Do not add by default:

- decorative gradients
- random neon glows
- oversized rounded cards
- unnecessary pills
- floating blobs
- glassmorphism everywhere
- excessive shadows
- motion that has no functional or narrative purpose

Use these only when the chosen reference or brand clearly justifies them.

---

# 3. Reference Source Map

Use the sources selectively. Never search all sources for a simple task.

## A. Visual direction and real-world taste

### Refero Styles
Best for:
- overall design direction
- landing pages
- editorial product pages
- typography
- palette
- spacing
- section rhythm
- premium visual systems

If live Refero tools are available, use them first for visual work.

Prefer multiple references and choose one dominant style.

### Minimal Gallery
Best for:
- high-end web references
- layout inspiration
- typography-led compositions
- whitespace and editorial rhythm

Use as a visual benchmark, not as a component source.

### Kage
Best for:
- translating a UI feel or design language into promptable design attributes
- decomposing references into reusable visual instructions

Use only when the site/tool is accessible and relevant.

---

## B. Cinematic, scroll-driven and 3D web

### Scrolltide
Best for:
- cinematic hero sections
- scroll-driven landing pages
- cursor interactions
- animated backgrounds
- 3D-inspired UI
- interaction prompts
- motion concepts

Use public descriptions and user-provided/licensed prompts only.

Do not reproduce premium prompt text or paid source code without the user's licensed source.

Extract the physical interaction model.

Examples:
- pointer attracts a field
- scroll scrubs a sequence
- media reveals through a mask
- depth shifts with cursor position
- sticky scene changes state by scroll progress

Describe the mechanism, not only the adjective.

---

## C. Production components and UI patterns

### shadcn/ui
Best for:
- production-grade UI primitives
- forms
- dialogs
- tables
- menus
- accessible application UI

Use as an implementation foundation when appropriate.

### Aceternity UI
Best for:
- marketing-site motion
- visual effects
- premium animated sections
- interactive cards and backgrounds

Use selectively. Avoid stacking several high-intensity effects together.

### Magic UI
Best for:
- animated marketing components
- CTA effects
- lightweight motion accents
- modern product-site sections

### Motion Primitives
Best for:
- interaction and motion primitives
- restrained component motion
- transitions
- layout animation

### Uiverse
Best for:
- isolated UI details
- buttons
- toggles
- loaders
- small interaction concepts

Treat community snippets as inspiration and review code quality/accessibility before production use.

### UIAble
Best for:
- general UI reference
- component structures
- common interaction patterns

### MicroKit UI
Best for:
- micro-interactions
- subtle component behavior
- small high-polish details

---

## D. Specialized interaction / effect sources

### Kinetics by Colorion
Best for:
- motion effects
- animated visual treatments
- React-oriented kinetic ideas

### Liquid Glass
Best for:
- refractive glass effects
- distortion/reveal concepts
- glass-like interaction

Use sparingly. Glass should have a functional or compositional role, not become a default surface treatment.

### CSS Text Effects by Colorion
Best for:
- text animation
- kinetic typography
- hover/reveal typography
- text-specific visual effects

Use only when readability remains strong.

---

## E. Maps

### mapcn
Best for:
- map components
- markers
- routes
- map popovers
- map-oriented interaction patterns

Use when the interface genuinely needs geographic information.

---

## F. Error / edge-state inspiration

### 404s.design
Best for:
- 404 pages
- empty/error-state visual ideas
- memorable fallback screens

Use the concept, not a pixel-identical copy.

---

# 4. Research Workflow

For substantial design work:

## Step 1 — Read project context

Collect or infer:

- product / page purpose
- audience
- primary conversion action
- brand colors and type
- existing site language
- implementation stack
- media constraints
- accessibility constraints

Do not ask again when the answer already exists in the current project context.

## Step 2 — Select the research track

Choose one primary track:

- visual direction
- hero / landing page
- component
- motion
- text effect
- map
- error state

Then choose the smallest relevant source set.

Typical source budgets:

- small component: 1–2 sources
- hero / section: 2–3 sources
- landing page redesign: 3–5 sources
- full product visual system: 4–6 sources

Do not browse 16 sites just because they are listed here.

## Step 3 — Build a reference ledger

For each useful reference, record:

- source
- page/component name
- why it is relevant
- visual thesis
- type behavior
- color/surface behavior
- spacing/density
- interaction model
- media treatment
- one detail worth adapting
- one thing not to copy

## Step 4 — Choose a dominant reference

Create a reference lock:

```
Primary direction:
Preserve:
- ...
- ...
- ...

Secondary reference 1:
Borrow only:
- ...

Secondary reference 2:
Borrow only:
- ...

Brand constraints:
- ...

Reject:
- ...

Media strategy:
- ...

Motion strategy:
- ...
```

Do not start implementation until this is coherent.

---

# 5. Implementation Routing

This skill owns visual research and design direction.

After the reference lock:

## React / Next.js
Use the relevant React/Next.js skill for implementation.

## shadcn
Use the shadcn skill when shadcn primitives are part of the build.

## Motion
Use the primary motion skill only after interaction logic is defined here.

Do not load several competing motion skills at once.

## Figma
Use the Figma-specific skill if the output must be authored in Figma.

## Existing production site
Preserve existing architecture, routes, SEO semantics, analytics and form behavior unless the user explicitly requests changes.

Visual redesign must not silently break:
- heading hierarchy
- metadata
- internal links
- tracking
- forms
- accessibility
- responsive behavior

---

# 6. Prompt Engineering for Visual Effects

When converting a visual idea into an AI coding prompt, use physical and measurable instructions.

Bad:
- "make it futuristic"
- "make it premium"
- "add cool animation"

Good:
- "Render a low-contrast dot grid on Canvas 2D. Within 180 px of the pointer, distort point positions toward the cursor using a smooth radial falloff. Outside the radius, points relax back to origin with spring damping."
- "Keep the base image blurred at 16 px. A 120 px circular pointer-following mask reveals the sharp layer beneath. The mask trails the cursor with 120 ms smoothing and disables on touch devices."
- "The heading enters by line, 18 px upward translation to 0, opacity 0→1, 520 ms duration, cubic-bezier(0.22,1,0.36,1), stagger 70 ms."

Prefer:
- dimensions
- timing
- easing
- opacity
- blur
- transform distance
- radius
- scroll range
- pointer distance
- spring parameters
- breakpoint behavior

Avoid adjective-only prompts.

---

# 7. Responsive Rules

Every design must define:

- desktop composition
- tablet behavior
- mobile portrait behavior
- touch fallback for hover/cursor effects
- reduced-motion behavior where appropriate
- text wrapping behavior
- image crop strategy
- safe component stacking

Do not ship a desktop-only interaction as the only way to access information.

---

# 8. Accessibility and Performance

Before handoff, check:

- contrast
- keyboard focus
- reduced motion
- semantic heading order
- button/link semantics
- touch targets
- image alt strategy
- animation CPU/GPU cost
- heavy shader/canvas fallback
- lazy loading for large media
- CLS risk
- mobile performance

A visually impressive effect that makes the page harder to read or materially slower is not a successful implementation.

---

# 9. Visual QA

After building, compare the rendered result to the reference lock.

Check:

- typography hierarchy
- whitespace rhythm
- section proportions
- content density
- image treatment
- surface hierarchy
- brand color discipline
- motion timing
- hover/touch behavior
- mobile composition

If the result looks generic, identify the exact decision that was averaged or lost and correct it.

Do not claim completion from source code alone when a rendered result can be checked.

---

# 10. Output Format

For a design request, return or internally produce this order:

1. Design brief
2. Reference ledger
3. Reference lock
4. Page/component structure
5. Interaction and motion spec
6. Production implementation
7. Visual QA findings
8. Final corrections

For a small UI tweak, compress this workflow but preserve the same logic.

---

# 11. Brand Override Examples

If the project already has a strict palette:
- do not import a reference's colors wholesale.

If the project forbids gradients:
- preserve that constraint even when a reference uses gradients.

If the project requires real photography:
- do not replace it with generated art, CSS illustration, or generic stock imagery.

If the project uses square/sharp geometry:
- do not introduce pill-heavy rounded UI because a component library defaults to it.

If the project has approved typography:
- use reference typography as hierarchy inspiration, not as a mandatory font swap.

---


# 12. Installed Named Style Packs

## Refero: OpenAI Editorial System

Reference:
`references/refero-openai-editorial.md`

Design tokens:
`references/refero-openai-editorial.tokens.json`

Source style ID:
`dc541737-8bf2-4b31-b729-0352f696e82f`

Use when the user asks for:
- OpenAI-like editorial restraint
- research-lab / publication-like clarity
- typography-led premium hero sections
- quiet hairline structure
- asymmetric editorial layouts
- low-chrome product or brand storytelling

For OCC, use this pack only as a structural reference. OCC brand colors, real coffee/origin photography, brand typography, and B2B conversion logic override the source palette and brand identity.

---

# 13. Final Rule

The workflow is:

`CONTEXT → RESEARCH → REFERENCE LOCK → IMPLEMENT → RENDER → COMPARE → CORRECT`

Not:

`PROMPT → GENERIC UI → ADD GLOW → DONE`

The user should get a site that looks intentionally designed for their brand, not a collage of component-library trends.
