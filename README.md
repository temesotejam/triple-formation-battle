# TRIPLE//SHIFT

A small browser-based formation combat prototype. It is a standalone HTML5 Canvas game with no build step or external runtime dependencies.

## Play

After GitHub Pages has completed its first deployment, open:

https://temesotejam.github.io/triple-formation-battle/

## Controls

- **WASD / Arrow keys**: steer the formation; assisted movement remains active.
- **1 / 2 / 3**: select A / B / C in sequence. The third selection locks one of six distinct forms.
- **V**: split or recombine into the current form.
- **X**: cancel an incomplete formation sequence.
- **Shift**: burst dash.
- **P**: pause.
- **Click an enemy**: set it as the priority target.

## Formation sequence

| Sequence | Form | Combat role |
|---|---|---|
| A-B-C | SABER | Balanced assault |
| A-C-B | LANCER | High-speed breaker |
| B-A-C | LONGSHOT | Precision artillery |
| B-C-A | BOMBER | Area suppression |
| C-A-B | AEGIS | Guard / counter |
| C-B-A | FORTRESS | Heavy siege |

A, B, and C are intentionally simple pixel-style units. The focus is on assisted combat, splitting, and order-dependent recombination.

## Deployment

The GitHub Actions workflow in `.github/workflows/pages.yml` deploys the repository root to GitHub Pages on every push to `main`.
