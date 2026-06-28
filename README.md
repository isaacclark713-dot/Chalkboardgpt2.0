# Call Sheet — Coach Brain v1

This is the first "coach brain" version of the call sheet app.

## What changed

This version adds a football knowledge layer above the raw play database:

- Concept series, such as Power Series, Wide Zone Series, Quick Game Series, Mesh/Man-Beater Series, Screen Series, etc.
- Base / constraint / answer roles for concepts.
- Defensive reaction tags, such as LB overflow, edge crash, safety insert, loaded box, overhang widen/squeeze, man, zone, and blitz.
- In-game answer boosting. After a play is logged, the app remembers the concept, series, result, and defensive reaction. The next suggestion pool is boosted toward answers from the same series.
- Suggestion cards now show a coach-brain note explaining the series and what the play creates.

## How to publish on GitHub Pages

1. Create a new GitHub repository.
2. Upload the contents of this folder, not the zip file itself.
3. Make sure `index.html` is in the root of the repository.
4. Go to **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select the `main` branch and `/ root` folder.
7. Save.

GitHub will publish the app as a static site.

## Important storage note

The app runs entirely in the browser. Saved playbooks, uploaded custom databases, corrections, scouting data, and in-game tracking are stored in the user's browser storage on that device.

Use the app's built-in download/upload backup feature to move the same playbook to another device.

## Files

- `index.html` — the full app
- `.nojekyll` — prevents GitHub Pages from trying to process the site with Jekyll
- `sample-data/global_unique_plays.csv` — sample expanded play database for upload testing
