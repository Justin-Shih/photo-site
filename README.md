# Photo Site

This repository is the stable GitHub Pages home for photography pages and public photo assets.

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

## Source Project

The working content project is:

```text
C:\Justin\Codex\projects\攝影拍照blog
```

Current source staging came from:

```text
C:\Justin\Codex\projects\攝影拍照blog\github-pages-assets\docs
```

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
