# Rai Sato — research portfolio

Personal research website for [rai.tokyo](https://rai.tokyo), built with Jekyll and the al-folio foundation.

## Content map

- `_pages/about.md` — homepage and research overview
- `_pages/research.md` — detailed research projects
- `_pages/publications.md` — publication index
- `_pages/cv.md` — web CV
- `_bibliography/papers.bib` — publication data
- `_config.yml` — identity, contact, and site settings
- `_sass/_portfolio.scss` — portfolio-specific design system
- `assets/pdf/rai-sato-cv.pdf` — downloadable CV

## Local preview

```bash
source .venv/bin/activate
bundle exec jekyll serve --livereload
```

Open `http://127.0.0.1:4000`.

## Publishing

Pushing website content to `master` runs `.github/workflows/deploy.yml`. GitHub Actions builds the site and publishes the generated files to the `gh-pages` branch.
