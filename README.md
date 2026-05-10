# seungukkang.github.io

Personal academic blog and research portfolio.

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
├── index.qmd            # Home
├── research/            # Publications
├── projects/            # Projects
├── notes/               # Notes (Paper Review / Post / Ideas / Scribbles)
├── talks/               # Talks
├── cv/                  # CV
├── about/               # About
└── docs/                # Rendered output → GitHub Pages
```

## Adding a Note

Create `notes/my-note.qmd` with frontmatter:

```yaml
---
title: "My Note Title"
date: 2025-05-10
categories: [Paper Review]   # Paper Review | Post | Ideas | Scribbles
description: "One-line summary shown in the listing."
---
```

## Deployment

Automatic via GitHub Actions on push to `main`.
