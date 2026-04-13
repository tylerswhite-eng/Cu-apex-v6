# CU APEX v6 — Credit Union Leadership Simulation

A single-file, browser-based executive simulation game for credit union leadership education.

## What's New in v6
- **Tutorial Mode** added to the landing screen — no login required
- All 4 executive roles (CEO, CFO, CLO, CMO) fully explorable
- Live calibrated simulation engine (identical to v5 multiplayer engine)
- CAMEL scoring + Growth Score → Apex composite (same weights as multiplayer)
- Financial statements, examiner commentary, leaderboard — all populate instantly
- Full glossary drawer (15 terms with definitions and formulas)
- Consistent navy/orange color scheme matching the main application

## Deployment

### Vercel (recommended — one click)
1. Push this repo to GitHub
2. Import at [vercel.com](https://vercel.com) — no build settings needed
3. Live in ~30 seconds

### Local
```bash
npx serve .
# open http://localhost:3000
```

## Stack
- Pure HTML/CSS/JS — zero build step, zero dependencies
- [Supabase](https://supabase.com) for multiplayer auth, sessions, real-time
- Google Fonts: Syne, IBM Plex Mono, DM Sans
