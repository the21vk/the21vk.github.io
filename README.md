# Vinay Kumar

Personal website built with Jekyll and GitHub Pages.

## Site contents

- Home page with a short bio and research overview
- Research page with current topics and methods
- Publications page with journal articles and preprints
- Misc Docs page for talks, posters, reports, and related files

## Local development

Install the Ruby dependencies and start Jekyll:

```bash
bundle install
bundle exec jekyll serve
```

The site will usually be available at `http://127.0.0.1:4000/`.

## Configuration

Key site settings live in `_config.yml`:

- `title`, `description`, `url`, and `baseurl`
- navigation links in `navigation_header` and `navigation_footer`
- author and social metadata for SEO
- the shared banner image used on the main pages

Page content is in the top-level Markdown files:

- `index.md`
- `research.md`
- `publications.md`
- `misc-docs.md`

Assets such as images, logos, and styles are under `assets/`.

## Deployment

This repository is structured for GitHub Pages. Push changes to the default branch and let the site build in CI.
