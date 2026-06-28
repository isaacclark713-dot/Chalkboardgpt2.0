# Call Sheet — Coach Brain v2

This version adds improved neutral-result logging to Coach Brain v1.

## What changed in v2

Neutral is now treated as **no value / no harm**, not as a failed concept.

When logging a play in the In-Game tab:

- **Success** still boosts the concept.
- **Neutral** now opens a diagnosis selector.
- **Failure** still opens the failure-reason selector.

Neutral diagnoses include separate run and pass options, such as:

- Run: no gain / stalemate
- Run: no movement up front
- Run: missed block
- Run: loaded box
- Run: LB fast flow / overflow
- Pass: incomplete / no harm
- Pass: drop
- Pass: missed throw
- Pass: covered well
- Pass: pressure / throwaway

## How neutral now works

Neutral results preserve the concept instead of cutting it.

Examples:

- **No-gain run**: the concept is preserved, exact repeat is cooled slightly, and the series answer can be promoted.
- **Dropped pass**: the concept is protected because the diagnosis is execution, not play design.
- **Covered pass**: the concept is only nudged slightly, while answers are promoted.
- **Loaded box / LB fast flow / edge squeeze**: the coach brain promotes the correct series answers.

This keeps a no-gain Power or Inside Zone from being treated like a bad call while still using the defensive information to suggest a better next answer.

## Coach Brain v1 features retained

- Concept series, such as Power Series, Wide Zone Series, Quick Game Series, Man-Beater Series, Screen Series, etc.
- Base / constraint / answer roles for concepts.
- Defensive reaction tags, such as LB overflow, edge crash, safety insert, loaded box, overhang widen/squeeze, man, zone, and blitz.
- In-game answer boosting based on last play + defensive reaction.
- Suggestion cards that show a coach-brain note explaining the series and what the play creates.

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
