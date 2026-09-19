# Wardogs Mortar Calculator

Static GitHub Pages-ready website.

## Fixed in this version
- Coordinate parser correctly reads numeric values from `x91, y100`.
- Automatic Pythagorean distance calculation.
- Paste button uses the Clipboard API on HTTPS and gives a Ctrl+V fallback when the browser blocks clipboard access.
- Named saved calculations.
- Optional cardinal direction / bearing.
- Saved calculations persist with browser localStorage.
- Load, edit, and delete saved calculations.
- Layout styled to match the supplied Wardogs reference screenshot.
- Blurred Wardogs background.

## GitHub Pages
Upload `index.html` and `wardogs-background.jpg` to the root of a GitHub repository, then enable:
Settings -> Pages -> Deploy from a branch -> main -> / (root).

The site should be served over HTTPS by GitHub Pages, which allows the Paste button to request clipboard access.
