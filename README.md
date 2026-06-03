# src/ — the website code

The actual website lives here. **Not built yet** (Step 6 of the build sequence in `../CLAUDE.md`).

## Planned structure (static site, no build step)
```
src/
  index.html            # Home
  our-firm.html         # Who We Are + team grid
  bankruptcy.html       # Bankruptcy overview
  family-law.html       # Family Law overview
  offices.html          # Locations
  contact.html          # Contact / schedule
  blog.html             # Blog index (stub v1)
  team/                 # attorney bio pages
  practice/             # sub-service pages (templated)
  css/styles.css        # single shared stylesheet (uses design-tokens.md)
  assets/               # site images (copied/optimized from ../reference/assets)
```
GitHub Pages serves `index.html` directly. Header/footer are repeated HTML partials (documented in
`../docs/layouts.md`) since there's no template engine — keep them identical across pages.

Build per `../docs/PRD.md`. Use copy from `../reference/SITE-DESCRIPTION.md`, voice from
`../docs/brand-voice.md`, visuals from `../docs/design-tokens.md`.
