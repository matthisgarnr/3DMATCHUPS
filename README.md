# 3DMATCHUPS

3D matchups visualization — live Polymarket odds rendered as a glass-cased ball pit with realistic physics.

## What it does

Two clear acrylic vitrines side-by-side, fed by glass funnel tubes that descend from a metallic ceiling. Real-time Polymarket odds drive how many physics objects pile into each side — basketballs for NBA, soccer balls for World Cup matches, oil drums for crude oil markets, gold bitcoin coins for BTC ⬆/⬇.

- Three.js + Rapier physics (WASM)
- Live data from Polymarket Gamma API
- Dot-matrix LED scoreboard with team-color text and live countdown
- Searchable market picker across NBA + soccer + WC tags
- GSAP entry loader

## Stack

- Three.js 0.160 (ESM via unpkg)
- @dimforge/rapier3d-compat 0.14
- GSAP 3.15 + SplitText + CustomEase
- Pure HTML/CSS, no build step

## Run

Serve the folder over any static HTTP server:

```
npx serve .
```

Open `http://localhost:3000/` in a modern browser (Chrome/Safari).

## Asset credits

Single-mesh GLB models for basketball, soccer ball, oil drum, and bitcoin coin. See `/assets/`.
