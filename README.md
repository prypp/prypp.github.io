# Peeraya P. — Portfolio

> Japanese–Thai interpreter, coordinator & translator (**JLPT N2**) — and the maker behind **ra-yeah!**, a personal art & design studio.

**Live → [prypp.github.io](https://prypp.github.io)**

A small, hand-built site with two linked pages for two audiences:

| Page | Link | For |
| --- | --- | --- |
| **Creative portfolio** | [`index.html`](https://prypp.github.io) | The full story — personality, experience, and ra-yeah! art & design work |
| **Résumé** | [`formal.html`](https://prypp.github.io/formal.html) | A clean, professional one-pager for job applications |

The two pages cross-link, so a recruiter can jump from the playful side to the formal CV in one click.

## About

I spent three years in reception & administration at a Japanese clinic in Bangkok, then four years in Japan — reaching business-level Japanese (JLPT N2) and real cultural fluency. Now back in Thailand, I freelance as a Japanese–Thai translator and use AI tools in my daily workflow. On the side I run **ra-yeah!** (illustration, 3D, LINE themes & stickers, e-reader skins) and write Japanese & English learning books.

## Built with

- **Hand-coded HTML, CSS & vanilla JS** — no framework, no build step, no template
- **AI-assisted** start to finish (Claude · Gemini · Codex) — written despite *no coding background*
- **Python (Pillow)** for preparing and cropping the artwork
- Hosted free on **GitHub Pages**

> This site itself is the demo: it shows how I pair language and coordination work with AI tools to ship something real.

## Craft details

- Scroll-reveal animations gated behind a `.js` class — full **no-JavaScript fallback**
- Respects **`prefers-reduced-motion`**
- **WCAG-checked** colour contrast on text
- A randomly featured artwork in the hero on each visit
- Responsive down to mobile; pointer-only flourishes (cursor glow, magnetic hover)

## Run locally

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

No dependencies — it's just static files.

## Project structure

```
index.html        Creative portfolio (pink "Bubblegum" theme, Cormorant + Hanken Grotesk)
formal.html       Professional résumé (Spring palette, Newsreader)
art-*.jpg         Gallery artwork (3D, illustration, e-reader skin)
me.jpg            Portrait
rayeah-logo.png   ra-yeah! wordmark
og.png            Social share image
themes.html, fonts*.html, layouts.html   Design-exploration scratchpads (noindex)
```

## Deploy

Push to `main` → GitHub Pages rebuilds automatically (a `.nojekyll` file is included so assets are served as-is). No CI, no build step.

---

© 2026 Peeraya Pu-Im · Designed & hand-built with AI — no template, no coding background.
