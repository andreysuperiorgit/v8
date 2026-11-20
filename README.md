# LS7 V8 · Four-Stroke, interactive

A working 3D model of a 7.0 litre pushrod V8 that runs in the browser.

**Live:** https://andreysuperiorgit.github.io/v8/

- Rev it with the slider, the on-screen pedal, the `W` key, or the R2 trigger of a game controller (browser Gamepad API).
- Glass, section and solid cutaways. Camera presets. Click a cylinder in the firing order to track it.
- Live readouts: stroke, chamber pressure, valve timing, p-V diagram, slider-crank geometry.

## How it was built

One HTML file. [three.js](https://threejs.org) from a CDN, no model files, no textures, no build step.
Written with Claude Code (Fable 5.2), which also opened the page in headless Chrome, took screenshots and fixed what looked wrong over several rounds.

## What is real and what is simplified

Real: LS7 bore (104.8 mm), stroke (101.6 mm), rod length, 90° bank angle, cross-plane crank with pins 90° apart, firing order 1-8-7-2-6-5-4-3, camshaft at half crank speed.

Simplified: chamber pressure follows an idealised cycle, valve timing has no overlap, ignition fires at top dead centre, and parts are not to exact scale. Don't use it to rebuild an engine.

## Run it locally

Open `index.html` in a browser.
