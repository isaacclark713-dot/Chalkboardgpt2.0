# Call Sheet — Coach Brain v11

Static single-page football play-calling app.

## v11 additions

- 30-second quick logging: one-tap Good / No harm / Bad buttons on each suggested play card.
- Detailed diagnostics are still available, but they are collapsed behind a "Detailed diagnosis / defensive tell" section.
- Anti-spam recognition logic: successful concepts stay hot, but repeated concepts are cooled so a real opponent does not sit on them.
- Hot-concept changeups: when a concept like Stick is working, the caller promotes related answers/changeups instead of repeatedly forcing the exact same call.
- Recognition notes on play cards explain when a concept is getting stale or when a call is being promoted as a changeup.

## Deploy to GitHub Pages

1. Create a new GitHub repository.
2. Upload `index.html`, `README.md`, and `global_unique_plays.csv`.
3. Go to Settings → Pages.
4. Choose Deploy from branch.
5. Select `main` and `/ root`.
6. Save.

The app stores playbooks and corrections locally in the browser. Use the app's download/export features to move a playbook between devices.
