# Beyond the Hype — Event Website

Landing page for the **Beyond the Hype** event series, hosted by [Scott Logic](https://www.scottlogic.com).

**Live site:** https://scottlogic.github.io/beyond-the-hype-event/

---

## About the event

AI is changing everything about the way we approach software engineering and product development. The technology has reached an inflection point, and the focus must shift — from augmenting developers with AI tools, to creating the environment in which AI can truly succeed.

We need to reshape our processes: away from ones designed around human strengths and weaknesses, toward new ones shaped around the strengths and weaknesses of AI. There are hard questions ahead with no easy answers — yet.

Join us for an evening of talks from practitioners and conversations with your peers — to share experiences, learn together, and start forming a picture of what our future looks like.

**Date:** 30 June 2026

---

## Repository structure

```
.
├── site/               # Published website (served via GitHub Pages)
│   ├── index.html
│   └── assets/         # Images and SVGs
├── context/            # Background content and copy
│   ├── elevator-pitch.md
│   └── speakers.md
└── .github/
    └── workflows/
        └── deploy.yml  # Auto-deploys site/ to GitHub Pages on push to main
```

## Development

The site is a single self-contained `index.html` file with no build step. To work on it locally, open `site/index.html` directly in a browser or serve it with any static file server:

```bash
npx serve site
```

## Deployment

Pushing to `main` automatically deploys the `site/` folder to GitHub Pages via the Actions workflow. No manual steps required.
