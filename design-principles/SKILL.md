---
name: design-principles
description: Grounded design-principle reference (visual hierarchy, UI principles, graphic design elements, aesthetics, golden ratio, user-centered design). Use when critiquing a design, making a layout/composition/color/typography decision, or wanting a real rationale ("why") behind a design choice instead of a generic AI default.
---

# Design Principles

A reference library distilled from established design-education sources, kept as
separate topic files with the reasoning and examples intact — not compressed rules.
Use this to ground design decisions and critiques in real principles rather than
generic AI-default aesthetics.

## When to use this skill

- Building or critiquing a UI screen, layout, graphic, or composition
- Explaining *why* a design choice is being made, not just what it is
- Reviewing someone else's design (yours, a teammate's, an AI-generated one) for
  hierarchy, consistency, or accessibility gaps
- Deciding on proportions, spacing, or type/color scales
- Running a design through a user-centered sanity check before treating it as done

This complements `design-inspiration` (which extracts palette/geometry/type/texture
*from a reference image*). Use `design-inspiration` when there's a visual reference to
pull from; use `design-principles` when the question is about the underlying rule or
rationale, independent of any specific reference.

## How to use it

Don't load every resource file for every task — pull only what's relevant to the
specific decision in front of you. Each file is self-contained with its own examples
and source link.

| Working on... | Read |
|---|---|
| Layout, composition, what draws the eye first, spacing/grouping decisions | `resources/visual-hierarchy.md` |
| A UI screen or flow — buttons, forms, navigation, accessibility | `resources/ui-design-principles.md` |
| A static visual — logo, poster, packaging, marketing asset, illustration | `resources/graphic-design-elements.md` |
| Whether a design's polish matches its usability, or general "does this feel right" | `resources/design-aesthetics.md` |
| Proportions — sizing relationships, type scale, spacing scale, logo/layout grids | `resources/golden-ratio.md` |
| Sanity-checking a concept or an AI-generated draft against real user needs | `resources/user-centered-design.md` |

A single task often touches two files — e.g., a new UI screen usually wants both
`ui-design-principles.md` (the interface mechanics) and `visual-hierarchy.md` (what
should draw attention first). A logo or brand asset usually wants
`graphic-design-elements.md` plus `golden-ratio.md` for proportion.

## Applying it

1. Identify what kind of decision is actually being made (layout? proportion? a
   critique? a sanity check?) and read only the matching file(s) above.
2. Apply the relevant principles concretely — cite which principle is driving a
   specific choice (e.g., "using proximity to group the filter controls separately
   from the results list") rather than applying them silently.
3. When critiquing an existing design (including an AI-generated one), run it through
   the `user-centered-design.md` question checklist before calling it done — polish is
   not the same as validated.
4. Usability and accessibility always outrank a stylistic principle (this is stated
   explicitly in the golden-ratio source and holds generally) — if a rule and
   usability conflict, usability wins.
