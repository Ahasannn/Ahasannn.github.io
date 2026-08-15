# ahasannn.github.io

Personal academic website of Ahasan Kabir — Ph.D. student in Computer Science at the
University of Central Florida, working on efficient AI inference and ML systems.

Live at **https://ahasannn.github.io/**

## Structure

Plain HTML/CSS, no framework, no build step:

- `index.html` — the entire site (single page)
- `styles.css` — all styling (light + dark mode)
- `assets/` — profile photo, CV, and publication PDFs

## Preview locally

```sh
python3 -m http.server 8000
# open http://localhost:8000
```

Or just open `index.html` in a browser.

## Deploy

Pushing to `main` triggers `.github/workflows/deploy.yml`, which publishes the site
to the `gh-pages` branch. GitHub Pages serves that branch. Nothing else to do.

## Updating content

Everything lives in `index.html` — edit the News list, Publications list, or bio
directly. To update the CV, replace `assets/Ahasan_Kabir_CV.pdf` with a new file of
the same name.
