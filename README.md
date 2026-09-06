# Bull Run — website

Landing page for **Bull Run: Market Runner** (iOS). One static HTML file, no
build step, no dependencies. Fonts come from Google Fonts; everything else is
in `assets/`.

```
index.html      the whole page
privacy.html    the privacy policy — the URL App Store Connect points at
assets/
  icon.png      the app icon, 512px
  run.png       a WALL run in progress
  roster.png    the roster, showing The Sentinel
  pit.png       the Pit home screen
```

## Publishing

This repo is served by GitHub Pages from `main` at the repository root:
**Settings → Pages → Source: Deploy from a branch → `main` / `(root)`**.

`.nojekyll` is present so Pages serves the files as-is rather than running them
through Jekyll.

## Before launch

The status pill in the hero reads **In TestFlight**. Swap it for an App Store
badge linking to `https://apps.apple.com/app/id6808306705` once the app is
approved.

## Screenshots

Captured 4 September 2026 from the iPhone 17 Pro simulator against a seeded
profile, using the app's debug launch arguments (`-showSheet roster`, `-floor`,
`-autoStart -god -mode wall`). Re-capture with the same method after any visual
change.

## Source

The page lives here; the game itself is in a separate private repository.
