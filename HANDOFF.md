# kevra-marketing — Handoff Document

**Last Updated:** June 1, 2026
**Owner:** Jose (SFC Group LLC / Santa Fe Construction)
**Repo:** github.com/Flecho10/kevra-marketing (private)
**Live URL:** https://trykevra.com

## What This Is
Static marketing website for KEVRA — the AI-powered OS for contractors.
Single `index.html` file + `vercel.json`. No framework, no build step, no node_modules.

## Tech
- Pure HTML/CSS/JS — no dependencies
- Inter font via Google Fonts
- Deployed on Vercel — auto-deploys on push to main branch

## Files
- `index.html` — the entire site (9 sections + footer)
- `vercel.json` — Vercel static rewrite config
- `logo.png` — KEVRA logo (transparent PNG, white text)
- `jose.png` — Jose founder photo (arms crossed, Santa Fe Construction polo)

## Key URLs
- `trykevra.com` → this marketing site
- `app.trykevra.com` → the KEVRA app (login/dashboard) — repo: kevra-test
- `beta.trykevra.com` → beta signup landing page — separate repo

## To Make Changes
1. Edit `index.html`
2. `git add . && git commit -m "your message" && git push origin main`
3. Vercel auto-deploys in ~30 seconds

## Design Rules
- Brand color: #0065CE (KEVRA blue)
- Font: Inter
- Dark hero: #0F1117
- Premium SaaS quality — Stripe/Linear/Notion level
- No frameworks, keep it as a single HTML file

## To Do / Placeholders
- [ ] Add real OG image for social sharing (og:image currently placeholder)
- [x] Jose's photo already added (jose.png)
- [ ] Privacy Policy page on trykevra.com (optional — footer links to app.trykevra.com)
- [ ] Terms page on trykevra.com (optional — footer links to app.trykevra.com)
- [x] Footer Privacy/Terms link to `https://app.trykevra.com/privacy-policy` and `/terms` (June 2026)
