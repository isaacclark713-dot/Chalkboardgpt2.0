# Call Sheet Coach Brain v12.1

This is the v12 Defensive Style Library build with a live-caller hotfix.

## Fix in v12.1
- `Suggest 3 plays` now uses a protected scoring path.
- Defensive style/profile scoring is treated as a soft multiplier and cannot break the caller.
- If a scoring layer fails, the app falls back to the normal Coach Brain call engine.
- If the full call engine ever throws, a safe down/distance fallback caller still returns playable calls from the active base playbook.

## GitHub Pages
Upload these files to your repository root:
- `index.html`
- `global_unique_plays.csv`
- `README.md`

Then enable GitHub Pages from the repository settings.
