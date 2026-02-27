# Repository Architecture

## Goal

Host the Bit Clean Typora theme assets, documentation, and submission material for `theme.typora.io`.

## Structure

- `bit-clean/`
  - Theme package directory.
  - `bit-clean-light.css` and `bit-clean-dark.css` are the installable theme files.
  - `markdown-demo.md` is the canonical screenshot/test document.
  - `preview/` stores gallery thumbnail and screenshots.
- `prompts/`
  - Reusable AI image prompts for generating thumbnail artwork.
- `submission/`
  - Draft post content for Typora theme gallery PR.
- `README.md`
  - Public project landing page for GitHub visitors.

## Content Flow

1. Edit and test CSS in Typora.
2. Render `bit-clean/markdown-demo.md` and capture screenshots.
3. Save images in `bit-clean/preview/`.
4. Push to GitHub.
5. Copy `submission/typora-theme-gallery-post.md` into `typora/theme.typora.io` PR and upload the same images.
