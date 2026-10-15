# Green Shipping Research Group – website

Static website (HTML + CSS + a little JavaScript, no build step).

## Structure

- `index.html` – the whole site. Pages are sections switched by the URL hash: `#home`, `#research`, `#publications`, `#team`, `#contact`.
- `assets/gsrg-mark.png` – logo mark (light backgrounds), also used as the favicon.
- `assets/gsrg-mark-reversed.png` – logo mark for dark backgrounds (footer, dark mode).
- `assets/logos/` – partner and funder logos.

## Publish with GitHub Pages

1. Upload these files to the root of a GitHub repository (branch `main`).
2. Repository **Settings → Pages → Build and deployment**: Source = *Deploy from a branch*, Branch = `main`, folder = `/ (root)`. Save.
3. After a minute or two the site is live at `https://<user-or-org>.github.io/<repository>/`.

## Editing

- Text: edit `index.html` directly (each page is a `<div data-page="...">` block).
- Placeholders still to fill are marked with `class="todo"`.
- Remove the yellow "Draft for review" bar (`<div class="draftbar">`) before going public.
