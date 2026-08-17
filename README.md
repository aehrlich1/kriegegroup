# Kriege Group website

A small, dependency-free Hugo port of the Kriege Group website. The content, images, routes, news archive, profiles, teaching page, and legal pages are stored locally; WordPress is not required.

The visual design is a lightweight, project-native adaptation of the Hugo Academic style. It keeps the academic typography and card-based presentation without importing HugoBlox or another theme framework.

## Local development

```sh
hugo server
```

Open <http://localhost:1313/>.

## Production build

```sh
hugo --gc --minify
```

The generated site is written to `public/`.

## Editing content

- General pages and profiles are in `content/`.
- News articles are in `content/news/`.
- The landing page is in `layouts/index.html`.
- Site-wide styling is in `static/css/main.css`.
