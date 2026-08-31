# Backups

This folder holds a copy of the previous version of `SmartMark.html` from just before each update is pushed, so any release can be rolled back to without digging through git history.

**Convention:** before overwriting `SmartMark.html` with a new version, the outgoing version is copied here as `SmartMark_vX.Y.html` (version number taken from the release notes in the file itself).

## Rollback

Copy the desired `backups/SmartMark_vX.Y.html` back over `SmartMark.html` at the repo root.
