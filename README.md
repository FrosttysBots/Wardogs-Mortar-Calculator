# Wardogs Mortar Calculator v4

GitHub Pages-ready static website.

## Bearing update
The save dialog now asks for the **numeric bearing only**.

Examples:
- `250` -> `250° W`
- `295` -> `295° NW`
- `063` -> `063° NE`

Compass sectors:
- 337.5°–359.9° / 0°–22.4° = N
- 22.5°–67.4° = NE
- 67.5°–112.4° = E
- 112.5°–157.4° = SE
- 157.5°–202.4° = S
- 202.5°–247.4° = SW
- 247.5°–292.4° = W
- 292.5°–337.4° = NW

The player only types the number. The website automatically displays the direction.

## Calculator
- Parses `x91, y100`, `X:91 Y:100`, `91,100`, etc.
- Calculates distance automatically.
- Uses `sqrt(dx² + dy²) × 100`.
- Paste buttons use the Clipboard API on HTTPS/GitHub Pages with Ctrl+V fallback.
- Named saved calculations persist in the browser.
- Load, edit, delete, and clear-all controls.


## v5 changes
- Added a compact About / Disclaimer section beneath the calculator.
- Credits the original mortar/artillery calculation video as the inspiration for the website.
- Added a direct **Watch Original Video** button.
- Clarifies that the site is a fan-made independent community tool and is not affiliated with or endorsed by Wardogs or the video's creator.
- Original video: https://www.youtube.com/watch?v=9X8U-eHCMgI
