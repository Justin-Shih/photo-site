# Photo Site

This repository is the stable GitHub Pages home for photography pages and public photo assets.

Status: **CANONICAL ACTIVE PUBLISHING TARGET**. All new photography events belong here.

Each photo event or shoot is published into its own folder under `docs/`, so future photo sets do not overwrite the root photo index.

## Current Public Structure

```text
docs/
  index.html
  .nojekyll
  20260704-f1a971b5/
    index.html
    *_blog.jpg
```

## Source Workflow

The private source and automation workspace is maintained separately from
this public publishing repository.

The first published assets were historically migrated from the archived
`photo-blog-assets` repository.

Do not publish new events back to that legacy repository.

## GitHub Pages Setup

Configure GitHub Pages as:

```text
Deploy from a branch -> main -> /docs
```

Expected URLs after deployment:

```text
https://justin-shih.github.io/photo-site/
https://justin-shih.github.io/photo-site/20260704-f1a971b5/
```

## Safety

- Do not publish original full-resolution private photo folders unless explicitly approved.
- Publish only curated or processed web assets intended for public use.
- Keep each photo event self-contained under `docs/<event-slug>/`.
