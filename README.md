# Gym Session Tracker

A dependency-free personal gym logger designed for iPhone Safari and GitHub Pages.

## Features

- Full Body A and Full Body B from the active two-day gym plan
- Week 1 priming, Week 2 restoration, Week 3 volume ramp, normal training, and running-TT taper phases
- Phase-specific working-set and RIR targets
- Pound-only weight entry and display
- Autosaved draft and session timer
- Per-set completion buttons with exercise-specific rest countdowns
- Sticky session and rest timers while scrolling through exercises
- Previous matching exercise shown across current and retired-program history
- Compact completed-session summary for screenshots
- Local JSON backup and restore
- Offline support after the first visit

Session data stays in the browser's local storage. GitHub Pages hosts only the app files and does not receive workout data.
Completed history from the retired three-day plan remains available, while its draft is kept separate from the new program.

## Run locally

```powershell
python -m http.server 8000
```

Open `http://localhost:8000`.
