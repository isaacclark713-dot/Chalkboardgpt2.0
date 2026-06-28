# Call Sheet Coach Brain v9

This version adds Play IQ tags and an opening-script question tree.

## What is new in v9

- Opening script is built around scout questions instead of fixed play slots.
- Live script caller still uses the same scoring engine as the In-Game caller.
- Script objectives ask things like: how do they handle motion, who is force, does the edge chase boot, can we isolate the apex, are they man or zone on 3rd down, and do they pressure empty/long yardage.
- Formation & Play Intent Tags now include Play IQ fields:
  - route family
  - read type
  - route timing
  - coverage fit
  - weak-vs tag
  - protection requirement
  - hot answer
  - install confidence
- Play IQ tags are auto-generated from formation/play/concept names and can be edited on the Data tab.
- Uploaded CSVs are auto-tagged and can also include expanded intent/Play IQ columns.

## GitHub Pages

Upload the contents of this folder to a GitHub repository, then enable Pages from Settings → Pages → Deploy from a branch → main / root.

The app is static. User data is stored in each browser's local storage. Use the app's backup/download feature to move a playbook between devices.
