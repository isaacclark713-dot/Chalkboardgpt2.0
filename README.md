# Call Sheet — Coach Brain v14.9

GitHub Pages-ready package.

## v14.9 changes

- Reworked the Philosophy page into a clearer Playbook Builder flow:
  1. choose Template or Custom
  2. pick an offensive system template
  3. set playbook size and system discipline
  4. tune personnel, formation style, run/pass band, motion, and core concepts
- Retired the old broad Identity control.
- Retired the Tempo & Aggression control from generation scoring.
- Hardened formation style sliders:
  - 0% removes that formation family from generation and live suggestions.
  - Formation family carries much heavier weight in playbook generation and in-game calls.
- Custom mode sets system discipline to 0 and uses sliders only.
- Keeps source-backed offensive profiles and localStorage-based persistence.

## Deploy

Upload this folder to a GitHub Pages repository. Keep `index.html`, `.nojekyll`, `global_unique_plays.csv`, and `global_unique_plays.json` together.
