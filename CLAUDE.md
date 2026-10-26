# CLAUDE.md

Static GitHub Pages site (`index.html`, custom domain in `CNAME`) for the
Hahne/Müller Japan trip, 31 Oct – 14 Nov 2026. It deploys from `main`.

## Updating from the sheet
- Source of truth: the Google Sheet "HCI Canvas/Program for Richard HAHNE 2026/10",
  CANVAS and Confirmation tabs. On CANVAS, cell colour gives the status
  (see the legend on the sheet: confirmed, requested, walk-in only,
  self booked, suggestions).
- For a confirmation, update the stop in `TRIP` (time, badge/badgeType, sub,
  notes, alert), move the entry between `WL_REQUESTED` and `WL_CONFIRMED`, and
  update its banner chip if one exists. Commit 84f4e14 (Ajimori) is the reference.
- Never alter the encrypted statement blobs or any map link (`q:` values).
- Before editing, check that `index.html` is the full page (~166 KB) and not
  a pasted text stub. If it is a stub, restore it from the last good commit.
- Show the diff and get approval before pushing to `main`.

## Changelog
Every change to `index.html` gets a dated entry in the `README.md` changelog,
newest first, in the same commit. The README is publicly served, so leave
out costs and statement details.
