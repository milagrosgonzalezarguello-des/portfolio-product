# Portfolio: how to work on it

Static site: `index.html` + `img/` + `cv.pdf` (source: `cv.html`). Deployed by Vercel from `main`.
Work on a branch; the owner approves before anything goes to `main`. Explain that the Vercel preview link is a draft, not a second portfolio.

## Case study structure (owner's decision, Nov 2026)

Every case follows the same five parts, in this order, with these names in the section bar (`data-part` on the heading):

1. **Summary**: "In 30 seconds" (problem, what I did, result) and one image right after it.
2. **The challenge**: why they called, what hurt. Only the problem. Nothing about what was built.
3. **The solution, and how I got there**: starts by naming what was built, then the steps and decisions.
4. **The impact**: metrics. Separate what the design moved from what the business reports.
5. **What I learned**: what I'd do better, what the AI got wrong, what I take with me.

LG (`#view-lg`) is the model. Reuse its blocks: `.pains` (cards with icon, number, title, short text), `.checks`, `.plat`, `.tl` with `data-tl` (timeline that lights up on scroll), `.areas`, `.flowline`, `.dec` (decision: not chosen vs chosen, plus why), `.tchg` (test finding next to a screenshot).

## Owner's feedback on LG, to apply to every case

- **No walls of text.** Break content into chunks: cards, checks, bullets. Each item gets a title and a one or two line description.
- **Icons on key cards**, polished, and related to what the card says.
- **No tables for stories.** A sequence of phases is an animated timeline that lights up on scroll. A choice between options is a visual comparison, not a three-column table.
- **Show what you say.** If the text mentions a flow, show a flow. If it mentions a screen or a change in the product, put a screenshot or a crop of it next to the text.
- **Label every list.** A reader must know at once what a group of items is (for example "what went into version one"). If it is unclear what something is telling, rewrite or remove it.
- **Keep problem and solution apart.** Describing the product that was built belongs in the solution, never in the challenge.
- **A recruiter or designer must get it fast.** Clear first, visual second, clever never.
- **Say at the top of the case that all screenshots are sanitized** when the work is under NDA.

## Voice

Written as the owner telling it herself: first person, simple, short sentences, human. No slogans, no "X, not Y" lines, no stacked triads, nothing that sounds like AI. English on the site; she writes to Claude in Spanish.

## Honesty

Never invent research, users, metrics or tools. Only use what is already on the site or what she states. If a figure or a claim is unconfirmed, ask her. Simplified sketches must be labelled as sketches.

## Other preferences

- Toolbox descriptions say how she uses the tool ("I use it to…"). axe and Loom were removed on purpose; accessibility checks name Stark only.
- Check changes on desktop and at phone width before committing.

## Added after the second round on LG

- **Annotate screenshots instead of writing loose paragraphs.** Use `.anno` (figure with `data-anno`): numbered pins on the capture and the same numbers in a short key under it. Place each pin beside what it points at, never on top of the text.
- **Prefer real captures over recreated demos.** She is not sure about the recreated "try the agent" demo in LG and wants a real screenshot there when she provides one.
- **Gradient is one of the agents in the Agentiv marketplace**, not a platform that contains it.
