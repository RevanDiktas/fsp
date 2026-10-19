# fsp — Fravash Sourcing and Production

Static site for fravash.ai. No build step: Vercel serves the folder as-is.

- `index.html` — landing page
- `app.html` — private-beta sign-up (served at `/app`)
- `vercel.json` — clean URLs

Deploy: import this repo in Vercel (Framework preset: Other), then add `fravash.ai` under Settings → Domains.

## Hero video
Drop your file at `hero.mp4` in the repo root (H.264, 1920×1080 or wider, muted, 10–20 s loop, ideally under 8 MB). The hero plays it automatically; until then it shows a dark stage.
