---
tags:
  - meta
  - workflow
---

# Adding New Content

## Quick Workflow

1. **Create** a new `.md` file in the right folder under `docs/`
2. **Add frontmatter** with tags at the top of the file
3. **Write** your content with `[[wiki-links]]` to other pages
4. **Preview**: `mkdocs serve` → open `http://localhost:8000`
5. **Publish**: `mkdocs gh-deploy` (or just push — GitHub Actions auto-deploys)

## Naming Conventions

- **Filenames**: kebab-case → `python-tips.md`, not `Python Tips.md`
- **Tags**: lowercase, no spaces → `tags: [python, beginner, windows]`
- **Links**: `[[file-name]]` for wiki pages, `[text](https://.../)` for external

## Frontmatter Template

```yaml
---
tags:
  - tag1
  - tag2
---

# Your Page Title

Content here with [[wiki-links]] to other pages.
```

## Attaching Files

```
Place images in:   docs/assets/images/
Place PDFs in:     docs/assets/pdfs/
Place code files:  docs/assets/code/

Reference them as:
  ![Alt text](assets/images/screenshot.png)
  [Download](assets/pdfs/guide.pdf)
  [Script](assets/code/script.py)
```