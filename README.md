# Call Sheet Coach Brain v13

v13 adds the **Master Game Database** import architecture for full play lists around the 15,000-row range.

## What changed

- Uploads now accept **CSV or JSON**.
- Full game databases are split into:
  - offensive plays
  - defensive plays
  - unknown rows
- Only offensive plays enter the offensive Coach Brain caller.
- Defensive plays are stored separately for future defensive call-sheet tools.
- Uploaded JSON rows can include `formation`, `play`, `family_guess`, `concept`, `formation_slug`, `play_slug`, and `play_url`.
- The offensive active playbook, team source, and master database remain separate.

## Recommended use

Use the included `global_unique_plays.json` as the master game database.

1. Open the app.
2. Go to **Data → Upload / Import Play Database**.
3. Upload `global_unique_plays.json`.
4. Choose one of these:
   - **Add offensive plays to master**: adds the offensive subset to the master database.
   - **Use offense as active base**: makes the offensive subset the call sheet source directly.
   - **Generate base from offense**: generates a smaller Coach Brain active book from the offensive subset.
   - **Save offense as team source**: saves it as a reusable source pool.

For live games, keep the active base playbook smaller than the full master pool when possible.
