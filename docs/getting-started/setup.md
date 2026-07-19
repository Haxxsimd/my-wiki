---
tags:
  - meta
  - setup
---

# How This Wiki Works

## How It's Built

- **Static site generator**: [MkDocs](https://www.mkdocs.org/) with [Material theme](https://squidfunk.github.io/mkdocs-material/)
- **Hosting**: GitHub Pages — free, public, accessible from any device
- **Editing**: Any text editor — VS Code recommended

## Key Features

| Feature | How |
|---|---|
| **Search** | Press `Ctrl+K` or click the search bar. Full-text across all pages. |
| **Tags** | Add `tags: [tag-name]` in a page's frontmatter. See [[tags]] for everything. |
| **Wiki links** | Write `[[page-name]]` and it becomes a clickable link at build time. |
| **Code blocks** | Fenced code with syntax highlighting + copy button on hover. |
| **Dark/light mode** | Click the sun/moon icon in the top bar. |
| **File attachments** | Images, PDFs, code files go in `docs/assets/`. |

## Directory Layout

```
my-wiki/
├── mkdocs.yml            # Site configuration
├── requirements.txt      # Python dependencies
├── .github/workflows/    # Auto-deploy on push
└── docs/                 # ← All your wiki content lives here
    ├── index.md
    ├── getting-started/
    ├── notes/
    ├── bookmarks/
    ├── code-snippets/
    ├── how-to/
    ├── tags.md
    └── assets/
        ├── images/
        ├── pdfs/
        └── code/
```