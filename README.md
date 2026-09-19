# Wardogs Mortar Calculator v3

GitHub Pages-ready static website.

## Important fixes
- Uses a new localStorage key so old prototype data cannot break the calculator.
- Calculates immediately on page load and whenever either coordinate field changes.
- Robustly parses `x91, y100`, `X:91 Y:100`, `91,100`, etc.
- Example `x91, y100` -> `x80, y100` outputs `1,100 m`.
- Paste buttons use the browser Clipboard API on HTTPS (GitHub Pages) and provide Ctrl+V fallback.
- Named saved calculations with optional cardinal direction/bearing.
- Saved calculations persist in the browser.
- Load, edit, delete, and clear-all controls.
- Styling follows the supplied Wardogs reference image.

## GitHub Pages
Upload `index.html` and `wardogs-background.jpg` to the root of the repository.
Then use Settings -> Pages -> Deploy from a branch -> main -> / (root).

If the old site appears after updating, use Ctrl+F5 once to force-refresh the page.
