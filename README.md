# Unravel Digital — Payroll Tracker

Internal semi-monthly payroll management tool for Unravel Digital.

## Features
- Track 20 employees across 24 pay cutoffs per year (15th & 30th)
- Quick toggle paid/pending status per cutoff
- Full employee detail panel with editable fields
- Add / remove employees
- Export to CSV or JSON (per cutoff, full year, or all data)
- Data persists in browser localStorage

## Deploy to Vercel

### Option 1: Vercel CLI
```bash
npm i -g vercel
vercel --prod
```

### Option 2: Vercel Dashboard
1. Go to vercel.com → New Project
2. Upload this folder or connect your GitHub repo
3. No build settings needed — it's a static site
4. Deploy

## Notes
- Data is stored in each user's **localStorage** — it is not shared across devices
- To share data across your team, consider adding a backend (Supabase, PlanetScale, etc.)
- For password protection, enable Vercel's built-in Password Protection in project settings
