# Beach Blooms — Audio Rights Pitch Site

Static one-page site. Plain HTML/CSS with a small, optional script. No build step.

## Publish on GitHub Pages
1. Create a new public repo (for example `beach-blooms`).
2. Upload **every file in this folder** to the repo root. There are no subfolders, so a plain drag-and-drop works.
3. Repo **Settings → Pages → Build and deployment**: Source = *Deploy from a branch*, Branch = `main`, folder = `/ (root)`. Save.
4. The site goes live at `https://taralush.github.io/beach-blooms/` within a minute or two.

## Before you share the link (checklist)
- [x] **Link previews:** already set to `https://taralush.github.io/beach-blooms/`. If you move to a custom domain, update those addresses in `index.html` and make a new QR code.
- [ ] **Author photo:** add `tara-lush.jpg` (4:5 portrait, about 600×750) and swap the placeholder `<div>` for the `<img>` tag in the AUTHOR PHOTO comment.
- [ ] **Covers:** both covers are already optimized. If the art changes, replace the files with the same names and regenerate `og-image.jpg` (1200×630).

## Where each asset goes
| File | Used for |
|---|---|
| `cover-*.jpg / .webp` | Book One cover (hero) |
| `prequel-cover-*.jpg / .webp` | Prequel novella cover (Books section) |
| `truck-blooms-*.jpg / .webp` | Flower truck photo, close-up (Series section) |
| `truck-side-698.jpg / .webp` | Flower truck photo, side view (Contact section) |
| `herbie-382.jpg / .webp` | Herbie the Brussels griffon (Book One sidebar) |
| `og-image.jpg` | Preview image shown when the link is texted or emailed |
| `tara-lush.jpg` | Author photo (you add this) |
| `orchid-spray.svg` | Hero corner accent, Series photo accent, Audio Rights backdrop |
| `orchid-bloom.svg` | Header mark, divider, pillar bullets |
| `favicon.svg`, `favicon-32.png`, `apple-touch-icon.png` | Favicon placeholders |

To swap a photo, save the new one with the same filename. Save a `.jpg` and a `.webp`, or delete the `<source>` line for that image in `index.html`.

## Notes
- The fonts (Fraunces, DM Sans) are hosted with the site. There are no outside requests. Both fonts use the SIL Open Font License; the license files are in ``.
- Animations are subtle and switch off for visitors who have "reduce motion" turned on.
- The page prints cleanly, if anyone prints it.
