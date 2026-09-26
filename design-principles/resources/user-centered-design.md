# User-Centered Design Questions

Source: [Figma — User-centered design questions to ask at every stage](https://www.figma.com/resource-library/user-centered-design-questions/)

## Why it matters (and why it's newly urgent)

The framing problem this article opens with: an AI-generated prototype comes back
polished, the flow makes sense, and it took 10 minutes instead of two weeks. Before it
ships, someone has to ask the question that matters most — *who is this actually for,
and does it solve their problem?* Polish signals completeness even when nothing has
been validated. As generation gets faster and cheaper, the questions a team asks
*before accepting output* matter more than they used to, not less.

User-centered design questions are prompts that keep decisions anchored in real user
needs, goals, and context — rather than internal preferences or whatever an AI tool
defaults to. The core idea traces to Don Norman's human-centered design and the
Nielsen Norman Group: design decisions should start with the user, not the solution.
These questions apply at every stage — discovery, ideation, prototyping, testing,
evaluation — not just the research phase.

## Ground it in real answers first

Questions only work if grounded in real conversations, not guesses dressed up as
insight.

- **Run structured usability interviews.** Ask open-ended questions about how people
  complete a task *today* — not leading questions about a feature you already want to
  build. Let people show you what they actually do rather than describe what they
  think they do, and leave room to follow up when something surprises you.
- **Use AI to synthesize, not to replace hearing it.** Once you have interview notes
  or transcripts, AI can spot cross-conversation patterns fast — but treat the output
  as a starting point your team still checks against what people actually said.

## Questions by phase

**Discovery & research** — figure out who your users actually are, not who you assume
they are.
- Who are we designing for, and what do we know versus assume about them?
- What problem are users trying to solve, and what do they do today instead?
- What's the context of use — device, environment, emotional state, time pressure?
- What do we still not know, and how will we find out?

**Ideation & design** — the question shifts from "who?" to "does this actually work
for them?"
- Does this concept address the user's real goal, or just a symptom of it?
- Are we designing for the user's context, or only the happy path?
- What assumptions are baked into this design, and which ones still need testing?
- Does this introduce any new friction we haven't accounted for?
- Are we designing for users with different abilities, devices, or familiarity levels?

**Prototyping & testing** — this is where you watch what actually happens instead of
guessing.
- Can users accomplish their goal without instruction?
- Where do users hesitate, backtrack, or get stuck?
- Are people interpreting the design the way you intended?
- What did users say they expected, and how did that compare to what happened?
- What would make this easier, clearer, or more intuitive?

Simulated AI feedback (multiple simulated perspectives) is useful for surfacing blind
spots *before* real users are involved — but it's a starting point for exploration,
not a verdict. Real prototyping with real people is what actually validates a UX
direction.

**Evaluation & iteration** — doesn't end at launch; these feed the next cycle.
- Are users completing their core tasks successfully?
- Where are they dropping off, and what does that pattern tell you?
- Has the user's context or need shifted since you shipped?
- What's the next most important thing to improve?

## Making this a habit, not a one-off checklist

- **Turn it into a design-review ritual.** The review question isn't "does this look
  right?" — it's "does this serve the user?" Keep the standing question set visible in
  every review.
- **Use it specifically to evaluate AI output.** When a tool produces a wireframe or
  prototype: Does this reflect what we actually know about our users? Does it solve
  the right problem? What does it assume that we haven't validated?
- **Document the answers, not just the questions.** The answers become the shared
  source of truth that design, dev, and product can reference later instead of
  relitigating the same decision three sprints on.
- **Feed answers back into the roadmap.** A user-centered process is a loop, not a
  one-time exercise — revisit the same questions once an update ships.

## Four common failure modes

1. **Designing for the team, not the user.** Familiarity quietly replaces user
   research as the standard for "intuitive" — what's obvious to people who use the
   product every day is often opaque to a first-time user. *Ask instead:* would a
   first-time user understand this without help?
2. **Treating AI output as a validated solution.** Visual polish signals completeness
   before anything has been tested — treat any AI-generated concept like a rough
   sketch worth testing, not a decision worth shipping. *Ask instead:* what real user
   evidence supports this design direction?
3. **Only asking these questions at the research phase.** They get attention during
   discovery, then quietly disappear once deadlines take over. Every design/engineering
   trade-off later is still a chance to check back. *Ask instead:* what do we know
   about our users that should influence this specific decision?
4. **Skipping the "why" behind user behavior.** Dashboards show *what* users do
   (where they click, where they drop off) without ever explaining *why* — teams patch
   symptoms instead of root causes. A drop-off could mean unclear copy, a hidden
   element, or missing information — each has a different fix. *Ask instead:* what was
   the user trying to accomplish when they stopped?
