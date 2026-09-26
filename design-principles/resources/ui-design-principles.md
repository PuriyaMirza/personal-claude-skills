# UI Design Principles

Source: [Figma — Seven essential UI design principles + how to use them](https://www.figma.com/resource-library/ui-design-principles/)

## Why it matters

"Good design goes unnoticed. Bad design frustrates users until they abandon your
product entirely." UI design principles are the overarching guidance for building
products people can navigate intuitively, on any device. Thomas Lowry's framing:
"Think of a user as someone asking you directions. If you just showed them a map and
expected them to memorize it, they'll probably get lost. But if you point them to a
sign that says their destination is this way, they can follow the signs from
there... UI design principles help you set up signs users can follow towards their
goals — one click, scroll, or interaction at a time."

Measured benefits: enhanced usability, better decision-making (a shared framework for
predicting user needs), increased efficiency (Figma's own data: participants with
access to a design system completed their design objective 34% faster than those
without one), and reduced cognitive load.

## The seven principles

### 1. Hierarchy
"I often compare designing a digital product or website to designing a book," Lowry
says. "On every page, navigational cues remind you of the title, chapter, and content
section, so you never get lost." The levers designers use: **font size/weight** (large
and bold stands out, emphasizes buttons and key info), **contrast** (directs users to
key elements), and **spacing** (creates visual interest, shows relatedness). "Be
intentional about what goes where on a screen, especially what users see first and
what they have to scroll to see. Your UI content hierarchy should reflect what the
user cares about most."

### 2. Progressive disclosure
Borrowed from UX flow design: sequence what's shown so the interface doesn't
overwhelm. Lowry's example — an onboarding flow that asks name, contact info, role,
industry, and interests all at once looks like a long form; you might give up before
starting. Sequencing it across a few screens changes that entirely. The catch: "give
users a way to orient themselves, so they know where they are and how many steps they
have to go" — progressive disclosure without a progress indicator just becomes a maze.

### 3. Consistency
A good interface feels familiar from the first click. Design systems create that
familiarity through repeated patterns — when a button looks and works the same way
everywhere, users stop thinking about the interface and focus on their task. "If one
UI button is suddenly bigger, users are going to wonder why. That irregularity adds to
users' cognitive load, creating hesitancy and confusion. So you need a good rationale
when you deviate from established patterns." Consistency compounds — it matters more
the further a user gets into a flow, not less.

### 4. Contrast
Used *strategically*, not everywhere: "For a critical piece of information, you may
introduce a higher, more jarring contrast to command the user's attention." Concrete
example: a "delete account" button in red against white grabs attention and reinforces
the weight of the action; a secondary action like "keep account" in gray avoids
competing for that same attention. Contrast is a scarce resource — spend it on the one
thing that should win.

### 5. Accessibility
Vision impairments affect more than one in four users worldwide, so accessible
contrast and luminosity aren't an edge case. Black text on white remains the standard
for a reason. Use contrast checkers/plugins rather than eyeballing it. WCAG-aligned
checklist: alternative text, appropriate padding, compatibility with assistive
technology, proper keyboard navigation, sufficient foreground/background contrast.

### 6. Proximity
Things that belong together should stay together — users perceive elements placed
close together as related, which creates a more intuitive flow. Streaming-service
example: play, fast-forward, and rewind sit in the same row because they're all
playback controls — but the quit button lives elsewhere entirely, specifically to
prevent an accidental click from interrupting the viewing experience. Proximity isn't
just about aesthetics; it's a guardrail against the wrong click.

### 7. Alignment
Clean lines read as professional. A strong grid establishes order and balance;
consistent alignment improves readability and makes navigation predictable.

## Four pro tips

- **Apply perspective.** Position elements to guide users through a logical sequence
  toward their goal — map the user flow first, then place elements to match it, not
  the reverse.
- **Make it effortless.** Good interfaces feel invisible: consistent navigation, clear
  feedback for every interaction, smart shortcuts like search where they help.
- **Apply shortcuts.** Speed up common tasks with keyboard shortcuts and quick-access
  tools.
- **Conduct testing.** Watch how people actually use the interface — regular testing
  catches problems early and confirms the design works for everyone, not just the
  people who built it.
