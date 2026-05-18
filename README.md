# House of Light Wiki

A local MkDocs wiki for the *House of Light* fantasy series, published via GitHub Pages.

## Local Setup

```bash
# 1. Install Python dependencies (one time)
pip install -r requirements.txt

# 2. Start the local dev server
mkdocs serve
```

Then open **http://127.0.0.1:8000** in your browser. The site hot-reloads on every save.

## Adding Content

| What | Where |
|------|-------|
| New character | `docs/characters/your-character.md` |
| New location | `docs/locations/your-location.md` |
| New lore entry | `docs/lore/your-entry.md` |
| World overview | `docs/world/index.md` |
| Timeline events | `docs/timeline/index.md` |
| Character images | `docs/assets/images/` |

Copy the structure from `docs/characters/example-character.md` for character pages (infobox, quote block, spoiler warning).

Add tags to any page with frontmatter:
```yaml
---
tags:
  - Characters
  - Female
---
```

After adding a new page, list it in the `nav:` section of `mkdocs.yml` so it appears in the sidebar.

## Publishing to GitHub Pages

Every push to `main` automatically builds and deploys the site via the GitHub Actions workflow (`.github/workflows/deploy.yml`).

To enable GitHub Pages on your repository:
1. Go to **Settings → Pages** on GitHub.
2. Set the source to **GitHub Actions**.

The live site will be at: **https://chellxffs.github.io/hol-docs/**

## Custom Styling

- Dark theme colors, infobox, and quote block styles are in `docs/stylesheets/extra.css`.
- The infobox uses raw HTML — see the example character page for the full template.
- Headings use the [Cinzel](https://fonts.google.com/specimen/Cinzel) font for a fantasy aesthetic.
