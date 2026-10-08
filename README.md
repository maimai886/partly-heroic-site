# 晴時多勇者 / 晴れ時々勇者 / Partly Heroic — website

Public website for the iOS game: landing page, privacy policy, terms of use and support, in
Traditional Chinese (default), Japanese (`/ja/`) and English (`/en/`).

Live: https://maimai886.github.io/partly-heroic-site/

## Filling in the placeholders

Everything that still needs a value is in **one file: [`_config.yml`](_config.yml)** (search for `TODO`):
support email, App Store link, effective date, iPad support. Edit it on GitHub, commit, and
GitHub Pages rebuilds the site in about a minute.

## How it is built

- GitHub Pages builds the site with Jekyll from the `main` branch, root folder. No build step to run locally.
- Pages: `index.html` (landing, copy in `_data/home.yml`), `privacy/`, `terms/`, `support/`, and the same under `ja/` and `en/`.
- Shared layout: `_layouts/default.html`, `_layouts/doc.html`; UI strings: `_data/i18n.yml`; style: `assets/css/site.css`.
- Bug reports go to this repository's Issues (`.github/ISSUE_TEMPLATE/`). Issues are public.

## Credits and licences

- Font: Cubic 11 (俐方體11號) by ACh-K, https://github.com/ACh-K/Cubic-11, v1.500, SIL Open Font License 1.1.
  `assets/fonts/Cubic_11.woff2` is the unmodified TTF converted to WOFF2; the licence is in [`assets/fonts/OFL.txt`](assets/fonts/OFL.txt).
- Game art (`assets/img/`) © 2026 Partly Heroic Team. All rights reserved; not covered by the font licence.
