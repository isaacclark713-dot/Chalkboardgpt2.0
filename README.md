# Call Sheet — Coach Brain v3

This version adds a live opening-script caller. The opening script is now a set of script objectives with down/distance variants instead of a fixed 1-through-12 list.

## What changed in v3

- Opening script now builds decision-tree style objectives.
- Each objective has situation variants for 1st & 10, 2nd short, 2nd medium, 2nd long, 3rd short, 3rd medium, 3rd long, and 4th short/medium.
- The user chooses the actual current down/distance, and the app shows the next script call for that situation.
- Logging the script call advances to the next objective and feeds the in-game tracking/read system.
- The old printable script list is still shown underneath for reference/copy/export.

## GitHub Pages

Upload the contents of this folder to a GitHub repository. In GitHub, go to Settings → Pages → Deploy from a branch → main → root.

The app stores user data in each browser's local storage. Use the app's download/upload playbook backup tools to move a saved setup between devices.
