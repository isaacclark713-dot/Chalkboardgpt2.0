# Call Sheet — Coach Brain v14

Single-file football call-sheet app with offensive playbook generation, live game calling, defensive-style scouting, and system-based offensive profiles.

## What's new in v14

- Adds a source-backed Offensive System Library.
- Built-in profiles:
  - Kyle Shanahan / Wide Zone-Keeper
  - Paul Johnson / Flexbone Option
  - Art Briles / Veer-and-Shoot Spread
- Profiles give soft boosts, not hard rules.
- Profiles influence:
  - playbook generation
  - opening script questions
  - in-game scoring nudges
  - sequencing notes
  - self-scout guardrails
- Adds Apply System Preset, Export System JSON, and Import System JSON.
- Keeps the master game database separate from the active offensive playbook.
- Supports CSV and JSON play imports.
- Handles larger master databases while keeping game-day playbooks capped at 400 plays.

## Deploy on GitHub Pages

1. Create a new GitHub repository.
2. Upload these files.
3. Make sure `index.html` is in the root of the repo.
4. Go to Settings → Pages.
5. Deploy from the main branch root folder.

The app runs fully in the browser and stores saved data in local storage on the user's device.
