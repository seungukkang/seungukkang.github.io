# seungukkang.github.io

Personal academic profile.

**Live site**: https://seungukkang.github.io

Built with [Quarto](https://quarto.org) · Deployed via GitHub Pages

---

## Local Development

```bash
# Install Quarto: https://quarto.org/docs/get-started/
quarto preview          # live preview at localhost:4200
quarto render           # build to docs/ (git-ignored)
```

## Structure

```
├── _quarto.yml              # site config
├── custom.scss              # design system
├── index.qmd                # About (single-page profile)
├── assets/
│   ├── img/                 # profile photo, emblems
│   └── cv/                  # CV PDF
└── .github/workflows/
    └── deploy.yml           # render & deploy to gh-pages
```

`docs/` is the local render output and is not tracked.

## Deployment

Automatic via GitHub Actions on push to `main`: the workflow runs `quarto render`
and publishes `docs/` to the `gh-pages` branch, which GitHub Pages serves.
