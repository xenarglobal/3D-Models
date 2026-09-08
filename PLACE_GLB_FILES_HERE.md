# /models — Place your .glb files here

This folder holds all 3D food models and poster images.

## What to put here

- `*.glb`  — 3D model files (binary glTF format)
- `poster-*.jpg` — preview images shown while models load

## Getting free models

See the main README.md for free model sources.

## Demo note

The demo menu.js points to Google's public sample models (hosted on modelviewer.dev)
so the app works immediately without downloading anything.

To use real food models:
1. Download a .glb from poly.pizza or sketchfab.com
2. Place it here (e.g. models/pizza.glb)
3. Update the "model" field in menu.js
