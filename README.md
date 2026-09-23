# Aphelion

A scroll-driven 3D website for a fictional space agency. It's built with three.js, with procedural planets and no image textures.

Scroll through one continuous camera flight: an Earth built from shaders, an orbital shipyard where the starship assembles as you scroll, a launch sequence with warp, and an interactive survey of all eight planets.

**Live:** https://jeroginaca.github.io/aphelion/

## Features
- Planet surfaces, clouds, city lights, atmospheres, the Sun and Saturn's rings are all GLSL shaders
- The starship assembles from blueprint wireframes, part by part, as you scroll
- Launch sequence with engine plumes, warp streaks and live telemetry
- Clickable solar system with real planetary data
- Bloom, chromatic aberration and film grain, plus optional synthesized ambient sound
- Responsive; respects `prefers-reduced-motion`

## Run locally
It's a single self-contained `index.html`. Open it directly, or serve the folder:

```sh
python3 -m http.server 8765
```

three.js loads from jsDelivr, so you need an internet connection.

---
Aphelion Interplanetary Agency is a work of fiction. The planetary facts are real.
