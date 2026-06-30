# Call Sheet — Coach Brain v14.19

Single-page football playbook builder and in-game play caller.

## v14.19 changes

- Core Concept Targets are now tag-driven rather than exact-name-only.
- Each play gets computed scoring tags from core concept, play intent, formation structure, personnel, run scheme, pass structure, route family, series, and stress tags.
- Generation, in-game play suggestions, and initial concept weights now use those tags.
- This keeps Power / Power O, Power Read, Power Pass, RPO Access, Option Run, Boot / Keeper, and Dropback concepts from being lumped together incorrectly.
- Generated playbooks now save compact `targetTags` for auditing/debugging.

Upload the contents of this folder to GitHub Pages. `index.html` is the app entrypoint.
