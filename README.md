# runtime1 — website

The public site for **runtime1**: an operating system where agents are the primitive.

Live at **https://0x89karan.github.io/runtime1-site/**

## What this repo is

Static HTML, CSS and one vanilla-JS file. No build step, no framework, no dependencies —
`index.html` is the page a browser gets. It is served by GitHub Pages straight from `main`.

| File | |
|---|---|
| `index.html` | the argument, the evidence table, project status |
| `thesis.html` | why agents as the primitive, and the two locked decisions |
| `zk-verification.html` | the verification ladder, what each rung proves, and what it does not |
| `architecture.html` | interactive runtime schematic |
| `roadmap.html` | tracks, shipped and open |
| `whitepaper.html` | the whitepaper as a reading document |
| `style.css` / `paper.css` / `app.js` | shared design system and interaction layer |

## "coming soon" links

The runtime1 source repository is not public yet, so every link that pointed into it is
rendered as a non-link labelled **soon** rather than left to 404. That is a deliberate choice:
a disabled anchor still invites a click and still shows a URL on hover, and a dead link is a
worse answer than an honest label. They become links when the repository opens.

## Editing

Edit the HTML and push to `main`; Pages redeploys. Keep two rules:

1. **Every claim names its seam.** The site distinguishes what is *enforced*, what is
   *declared*, and what is *not built*, and labels which is which. A claim that quietly upgrades
   itself is the failure this project exists to avoid.
2. **Numbers come from a run, not from memory.** Every figure on the verification page was
   measured; if one changes, re-measure rather than adjusting the prose.
