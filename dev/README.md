# dev

Work-in-progress build of SmartMark, kept in this folder on `main`. This is where v4 features get built and tested, live at https://jarrayda.github.io/SmartMark/dev/SmartMark.html, before anything is promoted to production.

## Workflow

- All day-to-day work happens as commits directly to `dev/SmartMark.html`.
- Root `SmartMark.html` only ever holds shipped, production-ready releases, published live via GitHub Pages at https://jarrayda.github.io/SmartMark/SmartMark.html.
- When a dev checkpoint is ready to ship:
  1. Copy the outgoing production `SmartMark.html` into `backups/SmartMark_vX.Y.html` first (see `backups/README.md`).
  2. Replace root `SmartMark.html` with the new version and push — GitHub Pages picks it up automatically.

This keeps the production URL stable while `dev` moves freely. (A separate `dev` git branch was tried first but dropped — the folder alone already gives a live preview URL without the extra layer.)
