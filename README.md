# 🌀 Fractal Screensavers

Two stunning, dependency-free fractal screensavers in pure HTML/WebGL2. Double-click to run — no server, no build, no libraries.

## Versions

| File | Style | Zoom Depth | Features |
|------|-------|------------|----------|
| `index.html` | Classic / Elegant | 1e-12 | Smooth cosine palettes, Julia morphs, motion trails, vignette, grain |
| `neon-deepzoom.html` | Cyberpunk / Neon | **1e-13** | Double-single arithmetic, chromatic aberration, scanlines, neon palettes |

## Controls

- **F** or **Double-click** → Fullscreen
- **Space** → Pause
- **Esc** → Exit fullscreen
- **Mouse move** → Show controls hint

## Tech

- WebGL2 fragment shaders with Canvas2D fallback
- Adaptive quality (FPS-driven render scale + iteration depth)
- Curated zoom route through the most beautiful Mandelbrot boundary regions:
  - Seahorse Valley
  - Elephant Valley
  - Spiral regions
  - Feigenbaum dendrite
  - Mini-Brot regions
- Smooth iteration count (no color banding)
- Inigo Quilez cosine palettes with temporal morphing

## Performance

- Targets 60 FPS, never drops below 30
- Dynamically reduces render resolution and iteration depth on slower GPUs
- Pauses automatically when tab is hidden

## License

MIT
