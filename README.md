# Ball-exercise-challenge-


# 10-Day Ball Cardio Challenge

A single-file web app for tracking a 10-day ball exercise cardio challenge.

## Files

- `ball-cardio-challenge.html` — the whole app: HTML, CSS, and JavaScript in one file. No build step, no dependencies.

## Running it

Open `ball-cardio-challenge.html` in any modern browser. That's it.

To host it, upload the single file to any static host (Netlify, Render, Neocities, GitHub Pages, etc.) — no server or build process required.

## How it works

- Shows 10 days, each labeled "Ball Exercise."
- Tap a day to mark it complete (tap again to undo).
- A progress bar at the top tracks how many of the 10 days are done.
- Progress is saved in the browser's `localStorage`, so it persists between visits on the same device and browser.
- "Reset progress" at the bottom clears all completed days.

## Customizing

- To change the number of days or the label text, edit the `PLAN` array near the top of the `<script>` section.
- Colors, fonts, and spacing are defined as CSS variables at the top of the `<style>` section (`--bg`, `--coral`, `--lime`, etc.) for easy re-theming.
