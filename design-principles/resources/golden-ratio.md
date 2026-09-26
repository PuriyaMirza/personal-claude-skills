# The Golden Ratio in Design

Source: [Figma — What is the golden ratio + how can it elevate your designs?](https://www.figma.com/resource-library/golden-ratio/)

## Definition

The golden ratio (Φ) ≈ 1:1.618 is a mathematical proportion associated with aesthetic
harmony throughout history — from the Great Pyramid of Giza to the Pepsi logo. It
became formalized as part of design theory in the Renaissance and has influenced art
and architecture ever since.

Formula: **Φ = 1.618 = a/b = (a + b)/a**

Condition: split a line into two parts such that the ratio of the whole line to the
longer segment equals the ratio of the longer segment to the shorter one — both equal
1.618. This ties closely to the Fibonacci sequence: as Fibonacci numbers increase, the
ratio between consecutive terms approaches 1.618.

Historical origin: traced to Euclid and Pythagoras, with earlier possible use in
Egyptian and Mesopotamian architecture. Renaissance painters — notably Leonardo da
Vinci in works like *The Last Supper* and *The Annunciation* — explored it explicitly
in composition.

## Three ways to apply it

**Rectangles** — the golden rectangle grid maintains the 1:1.618 proportion through
six rectangular compartments, used as a foundational compositional structure. Its
modular structure divides infinitely into smaller pieces and underlies the circle and
spiral methods below.

**Circles** — drawn inside each rectangle segment of the golden rectangle grid, with
each circle's diameter matching the side length of its corresponding square. These
"golden circles" can also form a bullseye-like arrangement; even rearranged and
overlapped (as in many logos), they act as placement guides that maintain proportional
spacing between elements.

**Spiral** — a logarithmic spiral that grows outward while maintaining the 1:1.618
proportion throughout, constructed by drawing circular arcs through a series of
progressively smaller golden rectangles. The spiral guides a viewer's eye across a
composition, creating organic movement and drawing attention to focal points in a
natural, dynamic way — this is the version most people picture when they hear "golden
ratio."

## Where it shows up

- **Web design** — golden spirals help organize layouts to draw users toward CTAs;
  golden ratio grids inform button placement, column widths, and harmonious screen
  layouts.
- **Logo design** — many well-known logos are built from overlapping golden circles
  for natural balance. The golden rectangle also ensures a logo scales proportionally
  and consistently across screen sizes and print formats.
- **Art and architecture** — from the Taj Mahal to the Mona Lisa; used to divide a
  canvas, guide the eye, position focal points, and create balance.
- **Nature** — galaxy and hurricane spirals, leaf arrangement on a stem, nautilus
  shell whorls. Not a design technique here, but useful context for *why* the
  proportion reads as "natural" to a viewer.

## How to build it in Figma (manual method)

**Golden rectangle:**
1. Create a frame at your desired dimensions, keeping the width:height ratio at
   1:1.618 (e.g. 1,000px × 618px).
2. Duplicate and scale down proportionally by dividing width/height by 1.618 each
   time.
3. Repeat to build a nested series of golden rectangles.

**Golden ratio guides:**
1. Enable rulers (View → Rulers, or Shift+R).
2. Drag guides to match key divisions. For a 1,000px-wide frame: guides at 618px
   (1,000 / 1.618), 382px (618 / 1.618), 236px (382 / 1.618) — repeat the same math
   vertically.

**Golden ratio grid for layouts:**
1. Open Layout Grid settings (Shift+G).
2. Set column widths from golden divisions (1,000 / 1.618 = 618, then 618 / 1.618 =
   382, etc.).
3. Set rows using the same proportions for a balanced vertical structure.
4. Adjust margins/padding so elements align naturally to those proportions.

## When to use it — and when not to

Best suited for: logos and branding, photo/video composition (framing subjects so the
eye moves naturally through the image), typography (letting the ratio steer font-size
hierarchy and leading), web/UI layout grids and button placement, architectural and
interior spatial planning, and product/packaging composition.

**Avoid strictly following it** for highly abstract or extremely minimalist designs,
or any case where it would threaten usability or readability. This is the single most
important caveat in the source material: *usability and accessibility always outrank
the ratio.* It's a compositional aid, not a rule that overrides practical design
needs.

## Combining it with other principles (don't use it in isolation)

- **Rule of thirds** — a 3×3 grid vs. the golden ratio's 1:1.618 division. Best
  practice: place focal points where the golden ratio intersects the rule-of-thirds
  gridlines, for a more deliberate compositional anchor than either alone.
- **Grid systems** — column-based layouts can align to golden proportions; use golden
  rectangles specifically to define column widths for a harmonious structure.
- **Hierarchy and spacing** — apply phi scaling (×1.618) to font sizes, margins, and
  element spacing to define size relationships consistently across a design — this is
  a practical way to generate a type or spacing scale that feels coherent without
  arbitrary jumps.
- **Symmetry** — symmetry provides order; golden-ratio layouts provide structured
  asymmetry and visual interest. A common combination: symmetry for the main layout,
  golden ratio for the details.
