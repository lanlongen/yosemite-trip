# Yosemite Half-Day Trip Planner

A single-file static site (`index.html`) — no framework, no build step — for a half-day driving route through Yosemite. Mobile-first, share-friendly.

## Route
1. Yosemite Valley Lodge (driving break)
2. Tunnel View (drive-up viewpoint)
3. Glacier Point — *Glacier Point Road leg*
4. Washburn Point — *Glacier Point Road leg*
5. Taft Point (1.1 mi each-way hike) — *Glacier Point Road leg*

## Features
- Per-friend preferences panel (energy + priority), saved in `localStorage` — shows a tailored tip without reordering the route.
- Google Maps deep-links per stop, live-traffic SMS link, entrance-pass note.
- Photos hotlinked from Wikimedia Commons (`960px` thumbnails — the standard hotlink-allowed size) with footer attribution.

## Deploy
Static site. On Vercel: framework preset **Other**, no build command, output = repo root.
