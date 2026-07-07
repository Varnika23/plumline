# Plumline

A daily task companion web app: purple UI, a mascot named Plum, task scoring game rules (+2 on time, -1 if missed), daily/weekly performance review, and a Strava-style leaderboard.

Single self-contained HTML file — no build step, no dependencies. Open `index.html` directly, or view it live via GitHub Pages once enabled.

Uses the Claude artifact persistent storage API for saving tasks/profile and syncing the leaderboard, so it will only retain data when opened as a Claude.ai artifact rather than as a plain static file.
