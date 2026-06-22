# Big Two Arena

A standalone browser game for the Big Two card game (also known as Deuces, Dai Di, or Pusoy Dos).

## Features

- 2–4 player support with AI opponents
- Full 52-card deck
- Big Two ordering: 3 low, 2 high
- Validates singles, pairs, triples, straights, flushes, full houses, four of a kind, and straight flushes
- 3♦ opening rule
- Saved progress in localStorage
- Mobile-friendly responsive layout
- PWA manifest and service worker

## Run locally

```bash
python -m http.server 8090 --bind 127.0.0.1
```

Then open `http://127.0.0.1:8090/BigTwo/`.

## Files

- `index.html` — home screen and table UI
- `styles.css` — game styling
- `game.js` — rules, AI, rendering, and save/resume logic
- `manifest.webmanifest` — install metadata
- `sw.js` — offline caching
- `icon.svg` — original app icon
- `privacy.html`, `terms.html`, `credits.html` — basic public-site pages
