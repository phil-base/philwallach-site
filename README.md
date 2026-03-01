# philwallach.com

Personal site built with [Hugo](https://gohugo.io/). Deployed to GitHub Pages.

## Local Development

```sh
# Install Hugo (macOS)
brew install hugo

# Run dev server (includes draft content)
hugo server -D

# Production build
hugo
```

Site will be available at `http://localhost:1313`.

## Adding Content

**New page:** Create a markdown file in `content/`:
```sh
content/my-page.md
```

Use `draft: true` in front matter to keep content hidden from production.

## Deployment

Push to `main` — GitHub Actions builds and deploys automatically.
