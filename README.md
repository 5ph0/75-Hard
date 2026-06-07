# 75 HARD — Weight Loss Edition

Personal 75-day fitness programme tracker. Built as a Progressive Web App (PWA) — installs on Android like a native app, works fully offline.

## Features

- **75-day programme** with 4 training days per week
- **3 workout variations** per session type — rotates weekly so every week hits different muscle groups
- **All muscle groups covered** — chest, back, shoulders, arms, triceps, abs, legs, glutes, cardio
- **Day review popup** — auto-triggers after checking off a workout day (rating + freetext)
- **Weekly journal export** — copy all 7 days of reviews as formatted text
- **Day grid** — 75 cells with blue dot indicators for days with reviews written
- **Streak + progress tracking** — all saved to localStorage (offline, private)
- **PWA** — installs to home screen, works without internet

## Setup

### GitHub Pages (recommended)
1. Fork or upload this repo to GitHub
2. Go to Settings → Pages → Source: main branch → root `/`
3. Your app is live at `https://yourusername.github.io/repo-name`
4. Open that URL in Chrome on Android → 3-dot menu → **Add to Home Screen**

## File Structure

```
├── index.html      # Main app
├── manifest.json   # PWA manifest
├── sw.js           # Service worker (offline support)
├── icons/          # App icons (all sizes)
│   ├── icon-72x72.png
│   ├── icon-96x96.png
│   ├── icon-128x128.png
│   ├── icon-144x144.png
│   ├── icon-152x152.png
│   ├── icon-192x192.png
│   ├── icon-384x384.png
│   └── icon-512x512.png
└── README.md
```

## Data & Privacy

All data (progress, reviews) is stored in **localStorage** on your device only. Nothing is sent to any server. Clearing browser data will erase progress.

## Programme Structure

| Day | Session | Focus |
|-----|---------|-------|
| Mon | Upper Body | Push · Pull · Arms · Abs |
| Tue | Rest | Active Recovery |
| Wed | HIIT | Full Body · Cardio |
| Thu | Rest | Active Recovery |
| Fri | Lower Body + Core | Legs · Glutes · Abs |
| Sat | Steady-State Cardio | Zone 2 + Mobility |
| Sun | Rest | Full Rest |

Workout variations rotate A → B → C each week across all 11 weeks.
