# seungukkang.github.io

Personal academic profile.

**Live site**: https://seungukkang.github.io

Built with [Quarto](https://quarto.org) · Deployed via GitHub Pages

---

## Local Development

```bash
# Install Quarto: https://quarto.org/docs/get-started/
quarto preview          # live preview at localhost:4200
quarto render           # build to docs/
```

## Structure

```
├── _quarto.yml          # site config
├── custom.scss          # design system
├── index.qmd            # About
└── docs/                # Rendered output → GitHub Pages
```

## Deployment

Automatic via GitHub Actions on push to `main`.
