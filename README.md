# City2Surf 2026

Interactive trip page: George, Danny and Jimmy, Hyde Park to Bondi, 9 August 2026.

- `index.html` — the whole site (no build step)
- `photos/` — the seven weekend photos, named `01-start-line.jpg` … `07-recovery.jpg`

Served by a Cloudflare Worker (`city2surf-2026`) that reads this repo's `main` branch, so every commit goes live within a few minutes.
