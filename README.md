# Deep Dessert

Deep Dessert is a lightweight, browser-based planning map for **Dune: Awakening**. It is being focused on the upcoming single-player mode arriving on **September 22, 2026**.

The page provides a simple 9x9 coordinate grid for organizing points of interest and resources while preparing for solo play. It is intended as a quick visual aid for planning exploration, routes, and discoveries.

## Features

- 9x9 coordinate grid labeled A1 through I9
- Drag-and-drop map markers for:
  - Spice
  - Stravidium
  - Titanium
  - Caves
  - Labs
  - Shipwrecks
- Move markers between cells
- Prevents duplicate marker types in the same cell
- Supports up to four markers per cell
- Right-click a marker to delete it or clear its entire cell
- Automatically saves the current layout in browser `localStorage`
- Works as a static page with no build step or server required

## Running locally

Open [index.html](index.html) in a modern web browser. Drag markers from the palette onto the grid to build a personal planning layout.

Because the map is saved in `localStorage`, the layout is specific to the browser and device being used.

## Project structure

- [index.html](index.html): page layout, styling, interaction logic, and persistence
- `assets/`: SVG marker artwork used by the palette and grid

## Status and disclaimer

This is an unofficial fan-made planning tool for Dune: Awakening. It is not affiliated with or endorsed by Funcom or any other rights holder. Marker names and game references belong to their respective owners.

The single-player mode focus and September 22, 2026 date are the intended context for this project and may change as official game information develops.
