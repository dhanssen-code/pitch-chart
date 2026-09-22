# Pitch Chart

A dugout pitch-calling and at-bat charting app for the Valley baseball staff. Works on iPhone and iPad, installs to the home screen, and keeps charting even with no signal.

## What it does
- Call each pitch by type and location on a catcher's-view grid, then log the result (ball, called strike, swinging strike, foul, in play, hit by pitch).
- Tracks count, outs, innings, and pitch count automatically. Strikeouts and walks close the at-bat on their own; Undo fixes any tap.
- Shows each hitter's earlier at-bats today and in past games against the same opponent, plus scouting notes.
- Pattern watch flags predictable sequencing: repeated pitches, first-pitch habits, count tendencies, and pitch count warnings.
- Optional AI pitching coach (Claude) for next-pitch ideas, between-innings checks, and postgame reports.
- Chart view mirrors the paper game chart; Report view breaks down each pitcher's mix and results.

## Data
Games are stored on the device in the browser, not on GitHub. Export a backup from Settings after each game. The API key stays on the device and is never included in backups.

## Updating
Upload the new `index.html`, then change `VERSION` in `sw.js` (for example `pitchchart-v2`) so devices pick up the update. Open the app twice to load the new version.
