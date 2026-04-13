# CU APEX v6 — Credit Union Leadership Simulation

A single-file, browser-based executive simulation game built for credit union leadership education.

## Features
- **Tutorial Mode** — No login required. New users can explore all 4 executive roles, adjust decisions, and run the live simulation engine instantly.
- **Multiplayer Mode** — Full session-based play with Supabase backend, real-time updates, and facilitator dashboard.
- **CAMEL Scoring** — Regulator-realistic composite scoring (Capital, Asset Quality, Management, Earnings, Liquidity).
- **Financial Simulation** — Calibrated engine producing real balance sheets, income statements, and examiner commentary.

## Deployment

### Vercel (recommended)
1. Push this repo to GitHub
2. Import the repo at [vercel.com](https://vercel.com)
3. No build settings needed — deploys as a static site automatically

### Local development
```bash
npx serve .
```
Then open http://localhost:3000

## Tech Stack
- Pure HTML/CSS/JS — no build step, no framework
- [Supabase](https://supabase.com) for auth, sessions, and real-time multiplayer
- Fonts via Google Fonts (Syne, IBM Plex Mono, DM Sans)

## File Structure
```
index.html      — Complete application (single file)
vercel.json     — Vercel deployment config
package.json    — Optional local dev server
README.md       — This file
```

## Version History
- v6 — Added tutorial mode (no-login exploration of all roles + simulation engine)
- v5 — Calibrated simulation engine, facilitator dashboard, real-time multiplayer
