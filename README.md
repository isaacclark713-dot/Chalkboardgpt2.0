# Call Sheet — Coach Brain v10

This is the GitHub Pages-ready version of the Call Sheet app.

## What v10 adds

- Team/playbook CSVs can now be used like generated Coach Brain playbooks.
- A CSV can be:
  - added to the master database,
  - saved as a reusable team source,
  - used exactly as the active base playbook, or
  - used as the source pool for a generated Coach Brain base playbook.
- Fully custom books can be created inside the app with **Start blank custom book** and the existing manual play add form.
- Scout, Script, In-Game, Coach Brain, Play IQ, sequencing, audibles, and diagnostics all call from the active base playbook only.

## Publish on GitHub Pages

1. Create a new GitHub repository.
2. Upload the contents of this folder.
3. Go to **Settings → Pages**.
4. Choose **Deploy from a branch**.
5. Choose the `main` branch and `/ root`.
6. Save.

The app stores playbooks, tags, corrections, and game data in the browser's local storage. Use **Download playbook** inside the app to move a setup between devices.
