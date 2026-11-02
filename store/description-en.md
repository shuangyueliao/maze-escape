# Maze Escape — Store Submission Materials

## Short description (CrazyGames / GameDistribution / itch.io)

Escape procedurally generated mazes before time runs out. Three sizes,
optional fog-of-war, and 3 hidden stars to collect for a PERFECT escape.
Easy to learn, increasingly tense. How fast can you find the way out?

## Details

- Genre: Puzzle / Maze / Casual
- Controls: Keyboard (Arrows / WASD). Mobile: swipe on the maze or use the
  on-screen D-pad.
- Features: Perfect-maze generation (recursive backtracker), 3 sizes
  (11×11 / 17×17 / 25×25 with 60/150/300s timers), fog mode with ~3-tile
  vision radius, glowing exit gate, star collectibles in dead ends, minimap
  with explored footprints, per-size best-time saving, procedural stone-wall
  textures and WebAudio sounds, single-file HTML5 (no external assets),
  works offline once loaded.
- Tech: Vanilla JavaScript, Canvas, WebAudio. No frameworks, no tracking.

## Tags
maze, puzzle, escape, labyrinth, casual, fog, retro, single-file

## CrazyGames submission checklist
- [x] Self-contained index.html (SDK loads only on crazygames domains)
- [x] gameplayStart / gameplayStop / loadingStart / loadingStop / happytime events wired
- [x] Responsive (canvas scales, portrait-friendly, touch D-pad + swipe)
- [x] No external links inside gameplay, no analytics
- [ ] Cover: generate 1280×720
- [ ] Screenshots: generate 1280×800

## itch.io
- Upload maze-escape-itch.zip, mark "This file is playable in browser",
  entry file: index.html, viewport: fits screen (canvas auto-sizes), kind: html
- Pricing: $0 (donations optional)
