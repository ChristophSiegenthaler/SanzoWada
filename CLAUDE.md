# Sanzo Wada — Color Combination Explorer

Single-file static web app (`index.html`). No build step, no dependencies, no package manager.

## Structure

- `index.html` — the entire app: CSS, HTML, and JS in one file

## Running

Open `index.html` directly in a browser. No server needed.

## Key concepts

- Color wheel is rendered on a `<canvas>` element using HSL
- Palette harmonies computed in HSL space (analogous, triadic, complementary, split, tetradic, Wada muted)
- "Wada muted" mode applies desaturation/lightness offsets inspired by traditional Japanese dyeing
- Clicking a hex swatch copies it to clipboard

## Style

- CSS uses design tokens via CSS custom properties (`--color-*`, `--border-radius-*`)
- Typography: Georgia for body, Courier New for labels/code
- Layout: single centered column, 860px max-width; wheel + palette in a two-column grid
