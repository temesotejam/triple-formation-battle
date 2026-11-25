# TRIPLE//SHIFT

A small browser-based formation combat prototype. It is a standalone HTML5 Canvas game with no build step or external runtime dependencies.

## Play

After GitHub Pages is enabled and the first deployment succeeds, open:

https://temesotejam.github.io/triple-formation-battle/

## First-time Pages setup

The repository owner has enabled Pages for this repository. If the first deployment has not yet completed, the latest commit triggers the workflow automatically.

Initial setup (already completed):

1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment → Source**, select **GitHub Actions**.
3. Save the setting.
4. Open **Actions → Deploy static game to GitHub Pages** and rerun the latest workflow, or push another commit to `main`.

The deployment workflow validates the inline JavaScript and publishes the repository root on every push to `main`.

## Controls

- **WASD**: steer the formation; assisted movement remains active.
- **Right / Down / Left arrow keys**: select A / B / C in sequence. The third selection locks one of six distinct forms.
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
