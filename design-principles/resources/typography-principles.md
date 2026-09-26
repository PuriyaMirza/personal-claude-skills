# Typography Principles

Sources: [Figma — Typography anatomy](https://www.figma.com/resource-library/typography-anatomy/), [Figma — Typography in design](https://www.figma.com/resource-library/typography-in-design/)

## Why this file exists

Default AI font choices are almost always Inter, Roboto, Open Sans, or system-ui —
not because they're expressive or right for a given brand, but because they're the
"safe" fallback when nothing constrains the choice. This file is the reasoning and
the actual craft vocabulary behind avoiding that. The specific fonts to use for a
given project live in `preferred-fonts.md`, kept separate since that list will grow
and change over time while these principles won't.

## The letterform vocabulary (why fonts differ structurally, not just stylistically)

Knowing these terms is what makes a font *pairing* decision — matching or
deliberately contrasting structure — instead of a font *vibe* decision.

- **Baseline** — the invisible line characters sit on; what alignment is measured
  against.
- **X-height** — the height of lowercase letters like "x". A taller x-height reads
  more legibly at small sizes — relevant for body text and UI labels specifically.
- **Cap height** — the height of uppercase letters; defines a typeface's overall
  visual proportion.
- **Ascender / descender** — the parts of a letter extending above (b, d, l) or below
  (g, p, y) the baseline. These influence how much line spacing a typeface actually
  needs.
- **Counter** — the open or enclosed negative space inside a letter (the hole in an
  "o" or "e"). Open counters read more clearly at small sizes; tight counters can blur
  together.
- **Serif** — the small decorative stroke at the end of a character. Serif fonts read
  as more formal/traditional; sans-serif reads as more modern/neutral.
- **Stem** — the primary vertical stroke in a letterform; defines apparent weight.

**Practical use**: when comparing two fonts for a pairing, look at these features
directly rather than judging by eye alone — a heading font with a short x-height and
tight counters paired with a body font of a very different structure will feel
mismatched even if both fonts are individually "nice."

## Font pairing & selection

- Choose typefaces that match the actual tone of the project — serious/professional
  vs. playful vs. editorial — not typefaces that are simply popular or default.
- Test any candidate typeface with real content, at the actual sizes it'll be used
  at, not just a name and a preview line. A font that looks great as a headline can
  fall apart at 14px body size.
- Look at what similar/competing products use — not to copy, but to notice patterns
  worth understanding before deviating from them.

## Visual hierarchy through type

- Headings > subheadings > body, sized deliberately: typical web sizing is body text
  around 16px, H1 headers around 48px — a large, explicit jump, not a subtle one.
- Hierarchy is reinforced by more than size alone: white space, alignment, color, and
  deliberate use of multiple typefaces/weights all combine to signal priority.
- Keep type sizes and weights *consistent* across the system — the same H2 style
  should look the same everywhere, the same way `ui-design-principles.md`'s
  consistency principle applies to buttons and spacing.

## Readability & legibility — concrete numbers worth remembering

- **Line height (leading)**: ideal is 1.125–1.2× the font size (112.5%–120%). Too
  tight and lines blur together; too loose and text feels disconnected.
- **Line length**: aim for roughly 40–60 characters per line for body text. Past 60
  characters, increase the line height to compensate — long lines need more vertical
  breathing room to stay readable.
- **Kerning** (space between individual character pairs) should be adjusted for
  visual consistency, especially at large display sizes where mismatched spacing
  becomes obvious.
- **Tracking** (uniform letter-spacing across a range of text) should generally be
  *increased* for all-caps text — caps read as cramped without it.
- **Avoid ALL CAPS for lengthy text** — it measurably reduces readability and reads as
  shouting; reserve it for short labels or emphasis.

## Color & contrast for type

- Pick brand-consistent colors with strong contrast, and actually test text against
  both white and black backgrounds before committing — the brand palette that looks
  great as broad color blocks may fail as text color.
- Bolder, brighter colors suit headings (short, attention-grabbing); neutral colors
  suit body text blocks (long, meant to be read comfortably, not to compete for
  attention).
- Follow WCAG contrast guidelines — same accessibility baseline as
  `ui-design-principles.md`, applied specifically to text-on-background contrast
  ratios.

## Weights, styles & spacing mechanics

- Font weight scale runs 100–900 in steps of 100 (Regular = 400, Bold = 700, etc.) —
  use this scale deliberately for hierarchy rather than defaulting to just
  regular/bold.
- Maintain consistent margins and padding around type across the whole system, not
  just within one component.
- Left-justify long-form copy (ragged right edge is easier to read than justified
  text, which creates uneven word spacing); center-justify short elements like
  headings or pull-quotes where it reads more intentionally.
- Watch for "danglies" (widows/orphans — a single word or short line stranded at the
  end of a paragraph) and adjust the text box width to avoid them; a small width
  tweak usually fixes it.

## The standing rule for this system

Before generating any UI, state which font pairing applies — check
`preferred-fonts.md` first, never let a font choice get invented from scratch. If a
project genuinely doesn't fit an existing pairing, that's a signal to add a
deliberate new entry to that list rather than let one-off font choices accumulate
project by project outside the system entirely. Tie the type scale itself to
`golden-ratio.md`'s phi-based scaling rather than arbitrary size jumps.
