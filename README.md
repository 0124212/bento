# bento — 12.log

Single-HTML personal landing page. Zero frameworks, zero tracking, zero analytics, zero cookies — just `index.html` + CSS + a little JS. Deployed to Cloudflare Pages.

Live: `12.log` · Source: this repo

## Bento grid

12-column grid with cards: clock (multi-TZ), goals, bookmarks, site stats, streak, uptime, learning, now-playing, mood, reading, hot take, quotes. Responsive: collapses to single column on mobile.

## Features

- **Bento layout** — hero + side + tall/wide/med/sm cards, `fadeUp` + blur, hover lift + glow
- **6 themes** — light/dark + neon / vaporwave / miku / halloween / christmas / midnight (all in CSS vars)
- **45 easter eggs** — konami code (`↑↑↓↓←→←→BA`), matrix rain, hidden commands, secret URL paths (`#secret`), right-click toast, scroll progress, grain overlay
- **FX** — Web Audio SFX (click/hover/ding), cursor trail + burst, confetti, scroll-based card rotation, magnetic pills, rainbow mode, long-press ripple
- **Local stats** — visitor counter + eggs/konami counts in `localStorage`, no server

## Running

```bash
python -m http.server 8080
# or just open index.html
```

## Hints

Type `help` on the page for commands. Konami code works 5× for secret bento. There's something at `#secret` and `#secretBento`.

## Stack

No build step. Fonts: Space Mono / Inter / Rajdhani via Google Fonts. Icons: custom + emoji.

## License

MIT
