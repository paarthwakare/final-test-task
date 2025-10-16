# Tissot Watch – Interactive Configurator Demo

## Overview
A single-page web app that showcases a Tissot-style analog watch with an interactive, fully client-side configurator. Users can:
- Rotate and tilt the 3D-styled watch preview (drag to rotate, mouse move to tilt).
- Customize strap type and color (leather, steel bracelet, or fabric).
- Choose case material (steel, gold PVD, black PVD).
- Pick dial colors with instant visual feedback.
- Toggle luminous markers for night mode.
- Switch between live time and a classic 10:10 presentation, with either sweeping or ticking seconds.
- Adjust visual case size.
- Add to cart and save configuration (stored in localStorage).

Everything is self-contained (no external images or libraries). The watch is an inline SVG with animated hands and configurable styling via CSS variables and JavaScript.

Note: Tissot is a trademark of its respective owner. This app is an educational demo, not an official product page.

## Setup
No build or server required.

1. Download or copy the repository files.
2. Open index.html in any modern browser (Chrome, Edge, Firefox, Safari).

Optional:
- If you use a local web server, simply serve the folder and navigate to index.html.

## Usage
- Interact with the watch:
  - Drag on the watch to rotate around X/Y.
  - Move your cursor over the stage to apply a subtle tilt.
- Customize:
  - Strap: choose Leather, Steel Bracelet, or Fabric. If Steel is selected, color is pattern-based and the manual color input is disabled.
  - Case material: click a swatch to pick Steel, Gold PVD, or Black PVD.
  - Dial: click preset buttons or pick any color with the color input.
  - Size: adjust the slider to scale the visual representation.
  - Time: toggle Live time. If off, the watch shows 10:10:36. "Sweep seconds" controls second-hand motion when live time is on.
  - Night mode: toggle luminous markers glow.
- Cart and persistence:
  - Click Add to cart to simulate a purchase; the cart badge increments.
  - Click the Cart button to see a toast summary.
  - Click Save configuration to store your current setup in localStorage (auto-saves also occur on changes).
- Pricing:
  - Base price is $695. Price adjusts by case material and strap choice:
    - Case: Gold PVD +$150, Black PVD +$100, Steel +$0.
    - Strap: Steel Bracelet +$120, Fabric −$30, Leather +$0.
  - A strikethrough price appears when the Fabric strap discount applies.

Enjoy experimenting with different styles and options.