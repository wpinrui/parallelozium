# Parallelozium

An interactive browser applet for exploring the properties of trapeziums — built for teacher demonstration with 13-year-olds.

**Live demo → [parallelozium.netlify.app](https://parallelozium.netlify.app/)**

## What it does

- Draws a trapezium with a fixed 8 cm base and a variable top side (4–12 cm, 0.1 cm steps)
- A second slider translates the top side left or right (±5 cm, 0.1 cm steps)
- Angle arcs with degree labels update live at all four vertices
- Three checklist cards light up green as the shape satisfies each classification:
  - **Trapezium** — at least one pair of parallel sides (always satisfied)
  - **Parallelogram** — two pairs of parallel sides (top = 8 cm)
  - **Rectangle** — parallelogram with all right angles (top = 8 cm, offset = 0)

## Stack

Single `index.html` — no build step, no dependencies beyond CDN assets.

- [Two.js](https://two.js.org/) for the canvas
- [Nunito](https://fonts.google.com/specimen/Nunito) via Google Fonts
