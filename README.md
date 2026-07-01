# Coach Brain v15.8.3 Formation Depth Fix

Fixes generated playbooks spreading across too many thin formations.

Changes:
- Caps source-system formation spread more tightly for large generated books.
- Adds a final formation-depth pass: every kept formation must have at least five plays.
- Late RPO quota repair now prefers formations already in the book instead of adding one-off RPO formations.
- Runs formation legality after personnel/family repairs so those repairs cannot create 1–4 play formations.
- Keeps v15.8.x RPO classification fixes.
