# Avinash Kumar · portfolio site (draft)

Static single-page site. No build step: GitHub Pages serves `index.html` from the repo root (Settings → Pages → Deploy from branch → `main` / root). All links are relative, so it works at `https://avikr2000.github.io/` (repo AviKr2000/AviKr2000.github.io).

```
index.html               the page
assets/css/site.css      all styles (light/dark via prefers-color-scheme, responsive, print)
assets/fonts/            self-hosted Newsreader + Instrument Sans (OFL)
assets/img/              portrait-*.webp/.jpg, favicon.svg, favicon-32.png, apple-touch-icon.png, og-image.jpg
PROFILE_README.md        draft README for the github.com/AviKr2000/AviKr2000 profile repo (not part of the site)
```

Preview locally: `python3 -m http.server 8000` then open http://localhost:8000.

## Before publishing (search for `TODO`)
- [x] **Username**: AviKr2000, site at https://avikr2000.github.io/
- [ ] **Email**: hidden for now; uncomment the Email item in the Contact section of `index.html` and add the address.
- [ ] **LL.M.**: add institution and year (Credentials section, and ideally on LinkedIn Education too).
- [ ] **Content Strategist**: add organisation if there is one.
- [x] **Photo**: `assets/img/portrait-640|400.(webp|jpg)`, 4:5 crop, also used in `og-image.jpg`.
- [ ] **Politician names**: decide whether to restore them (see comment in the Experience section).
- [ ] **Employer rules**: check the employer's conduct rules on outside publications before posting writing pieces.

## Adding a writing piece
See the `HOW TO PUBLISH A PIECE` comment in the Writing section: copy a card, drop the `card--soon` class, add the link and date.
