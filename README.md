# Call Sheet — Coach Brain v15.1

GitHub Pages package for the Call Sheet Coach Brain app.

## Install on GitHub Pages

1. Upload every file in this folder to a GitHub repository.
2. In GitHub, open Settings → Pages.
3. Select the branch/folder that contains `index.html`.
4. Open the published GitHub Pages URL.

## v15.1 patch notes

- Removes duplicate Formation + Play entries from generated books.
- Filters defensive/coverage rows out of generated offensive playbooks.
- Formation hard rule: every included formation must have at least 5 unique plays.
- Formation hard rule: every included formation must include at least one run, one dropback/conversion pass, and one play-action/boot answer.
- Formation hard rule: formations must pass the selected system/sliders/package coverage before inclusion.
- Core concept sliders now seed actual plays into the generated book through tag matching, not only soft boosts.
- Keeps v15.0 formation-surface recognition, package coverage, and rank-lottery play suggestions.

If upgrading from an older version, regenerate the base playbook once so the new package rules and tag matching apply.
