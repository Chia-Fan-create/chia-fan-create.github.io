# chia-fan-create.github.io

Personal portfolio of Fran (Chia-Fan) Hsu. A single static page: plain HTML and CSS, no build step, no JavaScript.

## Publish on GitHub Pages

1. Create a public repository named exactly `chia-fan-create.github.io`.
2. Upload everything in this folder (`index.html`, `assets/`, `sitemap.xml`, `robots.txt`) to the `main` branch.
3. In the repository, open **Settings → Pages**, set **Source** to "Deploy from a branch", choose `main` and `/ (root)`, and save.
4. The site goes live at https://chia-fan-create.github.io/ within a few minutes.

## Updating content

- All text lives in `index.html`. Search for `TODO` to find spots that still need your input.
- Photos go in `assets/photos/` using the same filenames: `band-street.jpg` and `band-landscape.jpg` (16:9, 2000×1125, under 400 KB) and `portrait.jpg` (4:5, 1200×1500, under 300 KB). To change which part of a wide photo stays visible, edit `--pos` on its tag (for example `--pos: 50% 30%` keeps more of the top).
- Optional video loop: `assets/video/band-loop.mp4` (H.264, no audio, 3 to 6 seconds, 1600×900, under 3 MB). If the file is missing, `band-street.jpg` shows instead.
- Project screenshots go in `assets/projects/` (for example `tia-robot.png`, 1600×1000).
- Put your two résumés at `assets/Fran-Hsu-Resume-Analytics-Operations.pdf` and `assets/Fran-Hsu-Resume-Data-Science.pdf`.
- Colors and fonts are defined once at the top of the `<style>` block (`:root`). Dark mode values sit right below them.
