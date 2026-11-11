# Cumulus — Volumetric Cloud Simulator

A single-page WebGL 2 app that ray-marches volumetric clouds under a physically based sky. Everything lives in `index.html`; there is no build step and no dependencies.

## Run

Open `index.html` in a browser with WebGL 2 (or serve the folder with any static server).

## Features

- Scene presets (fair weather, golden hour, last light, overcast, above the deck, and more)
- Cloud controls: coverage, density, base height, layer depth, size, towering, wispiness, high cirrus, variation seed
- Sun elevation and azimuth, haze, silver lining, sky fill light, exposure
- Wind speed, direction and time-lapse rate; camera altitude and field of view
- PNG download up to 3840 × 2160, rendered as a multi-sample frame

## Controls

Drag to look around, scroll to zoom, `H` hides the panel, `Space` pauses motion.
