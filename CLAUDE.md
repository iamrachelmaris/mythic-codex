# Family Mythic+ Codex

- `app.html` = design + rendering code (`index.html` just loads it fresh). `data.js` = all content (S.holy / S.arcane / S.prot / S.hunter, GEAR, S.sam / S.mum).
- Updates from Warcraft Logs screenshots go in `data.js` only. Don't touch app.html for data changes.
- Only real data from Rachel. Never invent numbers, players, dates or advice. Every log entry has a date. Missing → "Not added yet".
- Light theme only. Must work on phones.
- After editing: commit and `git push` — GitHub Pages redeploys the live link in ~1 min.
- index.html is a loader; edit app.html for page changes. Each push: bump the `?v=` on `data.js` in app.html (and on any re-cropped image path) so browsers fetch the new version.
