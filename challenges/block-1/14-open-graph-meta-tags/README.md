# Issue #14 — Add Open Graph-style meta tags for social sharing preview

**Tier:** Advanced (6pt)

## What to build

Add `og:title`, `og:description`, and `og:image` meta tags to a page's `<head>` so it previews correctly when shared on social platforms.

## Requirements

- `<meta property="og:title" content="...">`
- `<meta property="og:description" content="...">`
- `<meta property="og:image" content="...">`
- Values are specific to the page's actual content (not placeholder text)

## Where to put your work

```
challenges/block-1/14-open-graph-meta-tags/(your-name)/index.html
```

## Definition of done

- Builds and displays correctly in a browser
- `<head>` includes valid, page-specific `og:title`, `og:description`, and `og:image` tags
- PR opened against `main`, linked to this issue (`Addresses #14`)

---

See [`example/index.html`](example/index.html) for a worked reference.
