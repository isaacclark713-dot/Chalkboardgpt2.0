# Call Sheet — Coach Brain v14.4

Single-file football call sheet / playbook generator.

## v14.4 changes

- Separates **Flexbone** and **Wingbone / Wishbone** as different formation-style sliders.
- Paul Johnson preset now treats **true Flexbone** as the hard scheme rail; Wingbone/Wishbone are adjacent changeups, not the same identity.
- In-game recommendations now weight formation identity more aggressively at high System Discipline.
- Legacy concept-family buckets are merged into the richer **Core Concept** system.
- Built-in database plays are reclassified into the fuller core-concept list before playbook generation and in-game scoring.
- Imported CSV/JSON rows are also reclassified into core concepts.
- Core option concepts include Triple Option, Inside Veer, Midline, Counter Option, Rocket Toss, Veer Pass, and Choice.

## Deploy on GitHub Pages

1. Upload this folder to a GitHub repository.
2. Make sure `index.html` is at the repo root or in the Pages source folder.
3. Enable GitHub Pages.
4. Open the published site in a browser.

The app runs entirely in the browser and stores saved playbooks in local storage.
