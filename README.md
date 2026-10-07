# FORGE

A workout planner and tracker for the PH-PPL program (Power/Hypertrophy Push-Pull-Legs). Runs in Chrome and installs to the home screen like a regular app.

This copy is shared by two people, each on their own phone. The user guide is `guide.html`, live at [lumen-drogulus.github.io/Forge-JonnyBo/guide.html](https://lumen-drogulus.github.io/Forge-JonnyBo/guide.html).

## Where the data lives

On each phone, inside Chrome. Nothing is sent anywhere, so two people using this copy never see or touch each other's records. Use **Settings → Back up data** to send a copy to Drive, email or a text. The app reminds you on the Home screen when a backup is overdue.

## Files

| File | What it is |
|---|---|
| `index.html` | The app's page |
| `guide.html` | The user guide for this copy |
| `js/config.js` | Whose copy this is. **The only app file that differs from the main FORGE.** |
| `js/data.js` | The program: workouts, exercises, tips, video links |
| `js/app.js` | Everything the app does |
| `js/figures.js`, `js/moves.js` | The animated exercise figures (generated files, don't hand-edit) |
| `css/` | The look |
| `sw.js` | Lets the app work offline and pick up updates |
| `manifest.json`, `*.png` | App name and icons |

## Updating from the main FORGE

Copy every file over this repo **except `js/config.js`, `guide.html` and this README**. Logged workouts are untouched: they live on the phones, not in these files. One upload updates both phones.
