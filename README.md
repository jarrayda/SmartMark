# SmartMark

GPS Waypoint & Track Manager — Deduplicate, Clean, Edit & Export

SmartMark is a single-file, offline-first web app for cleaning up GPS waypoints and tracks. Load a GPX, CSV, KML, or TXT file, find exact and near-duplicate marks, resolve same-name conflicts, edit tracks on an interactive map, and export exactly what you need — all processing happens locally in the browser, and nothing leaves your device.

## Features

- **Load & auto-analyse** — drop or browse a file; duplicates and conflicts are found immediately
- **Exact & near duplicates** — marks at identical coordinates or within a distance threshold are grouped so you can pick which to keep
- **Same name, different place** — marks sharing a name but far apart are flagged for rename or removal
- **Editable export names** — set a custom export label per mark without losing the original
- **Export options** — normalise to Proper Case, append today's date, choose coordinate format (DD, DDM, DMS), export as GPX, CSV, or KML
- **Clean Preview & Binned** — see exactly what will be exported and what will be removed before committing
- **Safe removal** — anything removed on export is automatically saved to a separate BinnedMarks backup file
- **Track Mode** — manage GPS tracks from the same file: view on an interactive Leaflet map, see distance and date range, keep or remove individual tracks
- **Track editing** — open a track in edit mode, draw a freehand lasso to select and remove points, trim bad GPS data (deleted points go to a BinnedTracks backup automatically)
- **Offline & private** — works fully offline after first load via a service worker; no data ever leaves your device

## Usage

Open [`SmartMark.html`](SmartMark.html) in a browser — no build step, no server required.

## Formerly

This project was previously named "Smart Re-Mark."
