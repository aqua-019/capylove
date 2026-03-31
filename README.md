# 🦫 CapyLove — Capybara Dating App (Tinder Clone)

A fully functional Tinder-style swipe dating app for capybaras. 746 real capybara images. Zero shame.

## Features
- **Tinder-style swipe cards** — drag or tap ✕/🌿/⭐
- **746 real capybara images** from capy.lol API  
- **373 male / 373 females** (exact 50/50 split)
- **Attraction scoring algorithm:**
  - 🧸 Fur Density — 35% weight
  - ⚖️ Weight Score — 30% weight
  - 📏 Body Size — 20% weight  
  - ✨ Vibe/Friendliness — 15% weight
- **Filters:** All / Female / Male / Top Tier / Chonks
- **Match system** — ~40-70% match rate based on attraction score
- **Matches gallery** — see all your capybara loves
- **Leaderboard** — Top 50 hottest capybaras with score breakdown bars
- **Persistent state** — likes/matches saved to localStorage

## Running Locally
```bash
# Needs a local server (CORS for JSON)
npx serve .
# or
python3 -m http.server 8080
```
Then open: http://localhost:8080

## Deploy
Works on Vercel, Netlify, or any static host. 
Just drag the folder to Netlify Drop.

## Stack
- Vanilla JS (no framework — pure speed)
- Single HTML file + JSON data
- capy.lol API for images (free, no key needed)
- 0 dependencies
