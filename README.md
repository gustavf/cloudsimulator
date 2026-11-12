# Cumulus — Volumetric Cloud Simulator

A single-page WebGL 2 app that ray-marches volumetric clouds under a physically based sky, above an animated sea that reflects the clouds and carries their shadows. Everything lives in `index.html`; there is no build step and nothing to install (the MIT-licensed mp4-muxer library is inlined for video export).

## Run

Open `index.html` in a browser with WebGL 2 (or serve the folder with any static server).

## Features

- Scene presets (fair weather, golden hour, last light, overcast, above the deck, and more)
- Cloud controls: coverage, density, base height, layer depth, size, towering, wispiness, high cirrus, variation seed
- Sun elevation and azimuth, haze, silver lining, sky fill light, exposure
- Sea: wave roughness and water colour; reflections of sky and clouds, sun glitter, cloud shadows
- Wind speed, direction and time-lapse rate; camera altitude and field of view
- PNG download up to 3840 × 2160, rendered as a multi-sample frame
- MP4 video up to 3840 × 2160: rendered offline frame by frame (multi-sample, with motion blur) for a chosen length and frame rate, encoded in the browser with WebCodecs

## Controls

Drag to look around, scroll to zoom, `R` (or the Randomise clouds button) generates a new cloud layout with the same settings, `H` hides the panel, `Space` pauses motion.
