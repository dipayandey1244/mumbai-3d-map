# Mumbai 3D Explorer

Interactive 3D map of Mumbai using OpenStreetMap-derived vector tiles, OpenFreeMap, and MapLibre GL JS.

## Run

From this directory:

```bash
python -m http.server 8000
```

Open http://localhost:8000 in a browser. Internet is required to load map tiles and JS libraries.

## Features

- 3D building extrusions where OpenStreetMap height data is available
- Tilt, rotation, zoom, and pan
- Preset views for South Mumbai, Bandra, and BKC
- Landmark markers and popups
- Responsive layout

## Notes

Map data © OpenStreetMap contributors. Map tiles provided by OpenFreeMap. MapLibre GL JS is open source. This is a map visualization, not a complete photorealistic city mesh. Heights may be missing or approximate. For production-scale deployment, review tile provider usage policies.
