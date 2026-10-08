# Family Mythic+ Codex

- `index.html` = design + rendering code. `data.js` = all content (S.holy / S.arcane / S.prot, GEAR, S.sam / S.mum).
- Updates from Warcraft Logs screenshots go in `data.js` only. Don't touch index.html for data changes.
- Only real data from Rachel. Never invent numbers, players, dates or advice. Every log entry has a date. Missing → "Not added yet".
- Light theme only. Must work on phones.
- After editing: commit and `git push` — GitHub Pages redeploys the live link in ~1 min.
- Each push: bump the `?v=` on `data.js` in index.html (and on any re-cropped image path) so browsers fetch the new version.
