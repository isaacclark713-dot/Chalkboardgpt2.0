# Call Sheet — Coach Brain v15.2

Patch for v15 generation stability and formation-package hard rules.

## Fixes in v15.2

- Fixes the Generate Base Playbook freeze/break caused by v15.1 formation hard-rule scanning.
- Pre-groups formation candidate pools so the generator does not scan and sort the full database once per formation.
- Keeps the v15.1 hard rules:
  - no duplicate Formation + Play entries
  - no defensive calls in offensive generated books
  - every included formation must carry at least 5 unique plays
  - every included formation must include at least 1 run, 1 dropback/conversion pass, and 1 play-action/boot answer
  - formations still have to fit the scheme, personnel gate, formation sliders, surface sliders, and package coverage rules
- Prevents the final validation step from slicing formations into illegal partial packages.
- Caps the number of repaired formation packages so a requested book does not balloon just because every thin formation gets filled to five plays.

## Deploy to GitHub Pages

Upload the contents of this folder to your repo root. `index.html` is the app entry point. `.nojekyll` is included.
