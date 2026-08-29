# Booth Plotter

A single-file tool for planning vendor market booth layouts. No build step, no dependencies —
`index.html` is the whole app.

**Live:** https://keslerj13.github.io/booth-plotter/

## What it does

- **Draw the space** in feet and inches, or start from a 10×10 / 10×20 / 8×8 / 12×12 preset.
- **Place blocks** — tables, canopies, grid walls, chairs, bins, or any custom size — and see
  what actually fits. Overlaps and anything crossing the walls are flagged.
- **Any angle.** Drag the grip above a selected block to turn it; 15° steps while snapping is
  on, any angle when it's off.
- **Free draw** odd shapes for irregular fixtures, and label anything ("Potted plant",
  "Julie's table") by double-clicking it.
- **Measure** gaps between things, with endpoints that snap to edges.
- **Clearance zones** — 36" behind a table for someone to stand — drawn in the block's own
  frame, so they follow it when it turns.
- **How many fit?** calculates a count for a given block and gap, and can tile the space.
- **Save layouts and reusable modules** to come back to at the next market.

Everything is measured in inches internally and displayed in feet and inches.

## Running it

Open `index.html` in a browser. That's it.

Saved layouts and modules live in that browser's `localStorage`, so they're per-device — use
**Save / Load** to copy a layout's JSON between devices.
