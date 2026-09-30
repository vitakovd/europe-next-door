# Europe Next Door – website

Static site: `index.html` + `assets/`. No build step. Upload the folder as-is to any host
(Netlify drag-and-drop, GitHub Pages, Vercel, or FTP to your existing hosting).

## Editing
- **Dates, times, venues:** the `EVENTS` list near the bottom of `index.html` (marked `EDIT HERE`).
  Leave `start`/`end` as `""` while a time is TBC.
- **Registration:** set `REGISTER_URL` to a form link (applies to all events), or add
  `register:"https://…"` to a single event. While empty, the button opens an e-mail to info@brandnewukraine.nl.
- **Texts:** every text exists twice, `<span lang="nl">` and `<span lang="en">`. Edit both.
- **Panel members:** the `SPEAKERS` list in `index.html` (name, role, photo, bio_nl, bio_en). Photos go in `assets/speakers/` (square, ~280 px).

## Visuals
`assets/forum-banner.jpg` and `assets/forum-square.jpg` come from the DG ENEST communications toolkit.
