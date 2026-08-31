# 🏅 Marathon: TBR Dream — Training HQ

Personal marathon training dashboard for the **TBR Dream Marathon, 14 Feb 2027**.

**Live site:** https://chrstnpljs.github.io/MarathonProject/

## What it does
- 24-week training plan (long run, upper/lower gym, easy run, pickleball)
- Daily quest check-ins with XP, levels and a streak
- Filipino meal plan with per-ingredient grams and macros
- Sunday batch-prep rotation + shopping lists
- Recovery tracking, progress charts, injury mode

## Notes
Single self-contained `index.html` — no build step, no dependencies.
Progress is saved in the browser's local storage (per device).
Live Strava/Garmin sync only works inside the Claude app; the web version
gracefully falls back to manual entry.
