# Learning Pulse

Static dashboard for the 2026 AI and Learning Needs Assessment.

`index.html` is the whole site: one self-contained file, no build step, no
dependencies at runtime.

## Publishing an update

1. Open the dashboard, load the UKG export.
2. Data tab, set a passphrase, click **Save locked dashboard**.
3. Replace `index.html` in this repo with the file it saved.
4. Commit and push. The site updates in about a minute.

## Before you push

This repository is public, which is what makes GitHub Pages work on a free
account. Anyone can read every file in it, and git history is permanent.

**Only ever commit an `index.html` that was saved with a passphrase.** An
unlocked file committed here cannot be taken back by deleting it later, because
it stays in the history.

The check: open `index.html` in a text editor and search for `"locked":true`.
If it is not there, do not push.

The passphrase is not stored in this repo and must not be. Send it to readers
separately from the link.
