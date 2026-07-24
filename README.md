# Icefields Explorer 5.1

A GitHub Pages site presenting the cycling journey in two complementary formats:

- **Explorer:** synchronized route, performance data, photographs, notes, timeline, and charts.
- **Journal:** a day-by-day photographic and narrative view.

See `UPLOAD_INSTRUCTIONS.md` before uploading.

## Key corrections in this release

- Clean root `index.html`, clearly separated from `assets/js/explorer.js`.
- Cache-busting asset versions to prevent browsers from showing an older deployment.
- Notes remain on the timeline and are not drawn as black map markers.
- Selectable street, topographic, terrain, satellite, and light map backgrounds.
- Normal trackpad scrolling moves the webpage instead of zooming the map.
- Cadence averages exclude zero-cadence coasting records for Garmin-compatible stage values.
- Release marker available at `release.json`.
