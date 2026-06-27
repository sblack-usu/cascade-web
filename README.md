# TauDEM-Inspired Flow Puzzle (Web)

This is a small HTML/CSS/JS recreation of the Unity flow-accumulation puzzle loop.

## Core gameplay

- Each tile has base runoff and one outflow direction (arrow).
- Current accumulation (center number) is computed from all upstream tiles plus the base flow of the tile.
- Target accumulation (bottom right number) is generated from a hidden DEM-like solved board.
- Click the left or right side of any tile to rotate outflow (left side rotates counter-clockwise, right side rotates clockwise).
- Win when all current accumulations match all targets.

## Run

Open `index.html` in a browser.

For local static hosting (optional):

- `npx serve web`
- or any static file server pointed at this folder.
