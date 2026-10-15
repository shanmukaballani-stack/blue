# BLUE — Launch Vehicle 01

An interactive engineering-visualization concept for a single-stage orbital launch vehicle. Explore the rocket and launch platform from multiple angles, inspect the internal tank and propulsion layout, and export the model as GLB, OBJ, or STL.

## Run locally

The viewer loads Three.js modules from jsDelivr, so it needs an internet connection. From this folder, start a local web server:

```powershell
py -m http.server 8000
```

Then open <http://localhost:8000> in a modern browser.

## Viewer controls

- Drag to orbit; scroll to zoom; right-drag to pan.
- Use the front, side, rear, and top buttons to select a camera view.
- Toggle the fuel cutaway, platform, and technical markings independently.
- Download GLB to retain the scene and materials, or OBJ/STL for geometry.

The vehicle is a visual concept model, not a manufacturing-ready or flight-qualified design.