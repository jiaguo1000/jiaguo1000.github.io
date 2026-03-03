# Jia Guo Personal Website

Personal website built with Jekyll and the Minimal Mistakes theme.

## Local development

This repository is intended to be used with the VS Code dev container.

Start the local site with:

```bash
bundle exec jekyll serve
```

Then open:

```text
http://localhost:4000
```

If you change `_config.yml`, restart the Jekyll server.

To verify production-only features such as analytics locally, run:

```bash
JEKYLL_ENV=production bundle exec jekyll serve
```

## Deployment

The site is deployed with GitHub Pages through GitHub Actions.

The deployment workflow is defined in:

```text
.github/workflows/pages.yml
```

## Content locations

- Home page: `index.html`
- About page: `_pages/about.md`
- Publications page: `_pages/publications.md`
- Posts index: `_pages/posts.md`
- Blog posts: `_posts/`
- Navigation: `_data/navigation.yml`

## Styling

- Theme selection is controlled in `_config.yml` with `minimal_mistakes_skin`
- Custom style overrides live in `assets/css/main.scss`

## Notes

- The site uses the gem-based `minimal-mistakes-jekyll` theme
