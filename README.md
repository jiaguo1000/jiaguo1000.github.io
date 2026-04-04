# Jia Guo Personal Website

Personal website built with Jekyll and the Minimal Mistakes theme.

## Local development

This repository is set up with a VS Code dev container. Open in VS Code and select **Reopen in Container** to start.

The dev container automatically runs:

```bash
bundle exec jekyll serve --host 0.0.0.0 --port 4000 --livereload --force_polling --watch --incremental
```

Then open:

```text
http://localhost:4000
```

If you change `_config.yml`, restart the Jekyll server.

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
- Projects page: `_pages/projects.md`
- Navigation: `_data/navigation.yml`

## Styling

- Theme selection is controlled in `_config.yml` with `minimal_mistakes_skin`
- Custom styles: `assets/css/timeline.css` (About page timeline), inline `<style>` blocks in `_pages/projects.md`
- Layout overrides: `_layouts/single.html` (removes self-referential title link)

## Notes

- The site uses the gem-based `minimal-mistakes-jekyll` theme
