# GreenShip – Maritime Energy Transition Research Group

Website of the GreenShip research group, School of Business, Maynooth University.
Static site (HTML + CSS + a little JavaScript, no build step).

## Structure

- `index.html` – the whole site. Pages are sections switched by the URL hash: `#home`, `#research`, `#publications`, `#team`, `#contact`.
- `assets/brand/` – GreenShip emblem, wordmark, favicon and the four theme icons.
- `assets/logos/` – partner and funder logos.
- `v4/` – GlasShip version with the definition of "glas" at the top of the home page, under the logo.
- `v2/` – GlasShip version with the "Why GlasShip?" story below the hero.
- `v1/` – the first (blue) version of the site.

## Publish with GitHub Pages

Repository **Settings → Pages → Build and deployment**: Source = *Deploy from a branch*, Branch = `main`, folder = `/ (root)`. Save.
The site is then live at `https://<user-or-org>.github.io/<repository>/`.

## Editing

- Text: edit `index.html` directly (each page is a `<div data-page="...">` block).
- Placeholders still to fill are marked with `class="todo"`.
- Remove the "Draft for review" bar (`<div class="draftbar">`) before going public.
