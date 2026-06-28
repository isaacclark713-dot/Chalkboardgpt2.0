# Call Sheet — Coach Brain v7

Static GitHub Pages version of the Call Sheet app.

## What's new in v7

- Adds a Formation & Play Intent Tags engine.
- Automatically infers play intent from formation name, play name, family, concept, personnel, and motion.
- Stores intent tags on uploaded CSV plays so new uploads behave like part of the app's database.
- Adds a user-editable Intent Tags table on the Data tab.
- Uses intent tags to decide which diagnosis questions to ask after a play:
  - motion response
  - run fit / box
  - coverage / shell
  - screen picture
  - draw picture
  - RPO conflict defender
  - play-action / boot response
  - quick-game leverage
  - shot picture
- Playbook backups now preserve corrections, custom database rows, and edited intent tags.

## Deploy to GitHub Pages

1. Create a new repository on GitHub.
2. Upload the contents of this folder.
3. Go to Settings → Pages.
4. Choose Deploy from a branch.
5. Select main and / root.
6. Save.

The app is static. User data is stored in the browser's local storage. Use the app's backup/download feature to move a playbook between devices.

## CSV upload

Minimum required columns:

```csv
formation,play
```

Useful optional columns:

```csv
family_guess,family,concept,personnel,pers,motion
```

Optional intent-tag columns are also recognized:

```csv
surface,motion_purpose,run_scheme,pass_structure,series,conflict_defender,primary_stress,play_type,action_family,point_of_attack,screen_type
```

If intent columns are missing, the app infers them automatically.
