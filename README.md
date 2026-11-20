# Minutes to Midnight: edition data

Data files for the Minutes to Midnight watch, plus the built app itself in `app/` so that installed copies can update. No source code, no accounts, no tracking.

- `index.json`: a small pointer to the newest edition (edition number, date, size, checksum).
- `latest.json`: the newest edition in full.
- `editions/`: every edition, kept as an archive.
- `app/`: the current built app file and a small version file (build number, size, checksum). The app checks this on launch and asks before installing anything.

Each edition is a set of short desk briefings compiled from public sources, with links to those sources, independent fact-check notes, and a clock per desk. The clocks are informed judgments, not measurements. Items marked "not checked" were not verified. This is information, not advice.
