# Field Planner — App

The app shell for **Jay's Field Planner**, served via GitHub Pages.

This repo contains **code only — no data**. All planner data lives on each
device (browser local storage) and syncs to the private `FieldPlanner` repo
using a personal access token entered in the app's Settings screen. Anyone
loading the public app URL gets an empty planner and has no way to reach the
private data.

| File | Purpose |
|---|---|
| `index.html` | The entire app — single file, no build step, no dependencies. |
| `manifest.json`, `sw.js` | PWA support: add to home screen, offline loading. |
| `icon-*.png` | App icons. |

**Live app:** https://jaywalker061707.github.io/FieldPlannerApp/

Docs, the design document, and the data file live in the private
`FieldPlanner` repo.
