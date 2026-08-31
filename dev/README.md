# dev

Work-in-progress build of SmartMark, kept on the `dev` branch. This is where v4 features get built and tested before anything is promoted to production.

## Workflow

- All day-to-day work happens as commits on the `dev` branch, in `dev/SmartMark.html`.
- `main` only ever holds shipped, production-ready releases at the repo root (`SmartMark.html`), published live via GitHub Pages.
- When a dev checkpoint is ready to preview or ship:
  1. Merge (or cherry-pick) the relevant commits from `dev` into `main`.
  2. Copy the outgoing production `SmartMark.html` into `backups/SmartMark_vX.Y.html` first (see `backups/README.md`).
  3. Replace root `SmartMark.html` with the new version and push `main` — GitHub Pages picks it up automatically.

This keeps `main`'s history clean and the production URL stable, while `dev` can move freely.
