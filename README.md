# pomodoro.log

An LCARS-styled Pomodoro study timer. Single self-contained HTML file — no build step, no dependencies. Pick a subject, run focus blocks, and it logs your time so you can measure progress.

## Features

- **Focus / short / long block lengths**, configurable; long break every N blocks
- **Subject dropdown** (Bible study, Calculus, Spanish, Coding & AI, and more) — add your own
- **Automatic session log** — every completed focus block is recorded with date, start time, subject, and minutes
- **Progress panel** — total focused time, session count, day streak, and per-subject bars, filterable by today / week / month / all time
- **Radial gauge + segmented readout** for the running block
- **Synthesized LCARS-style sounds** on every control (no audio files)
- **Backup → Notes** (iOS share sheet) and **CSV export**
- Data persists in the browser; runs fully offline once loaded

## Run it

Open `index.html` in any modern browser. On iPhone, open it in Safari and use **Share → Add to Home Screen** for a full-screen app.

### GitHub Pages (optional)

With this repo's default branch set, enable **Settings → Pages → Deploy from branch → main** to serve the timer at a public URL — handy for adding to your phone's home screen.

## Notes

- The log is stored in the browser's local storage, so it lives per-browser on the device where you use it. Use **Backup → Notes** or **CSV export** for portable copies.
- No data leaves your device; there is no backend.
