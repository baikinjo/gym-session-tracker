# Gym Session Tracker

A dependency-free personal gym logger designed for iPhone Safari and GitHub Pages.

## Features

- Sessions A, B, and C from the current gym plan
- Re-entry mode with two working sets and 3 RIR
- Autosaved draft and session timer
- Per-set completion buttons with exercise-specific rest countdowns
- Previous matching workout shown beside each exercise
- Compact completed-session summary for screenshots
- Local JSON backup and restore
- Offline support after the first visit

Session data stays in the browser's local storage. GitHub Pages hosts only the app files and does not receive workout data.

## Run locally

```powershell
python -m http.server 8000
```

Open `http://localhost:8000`.
