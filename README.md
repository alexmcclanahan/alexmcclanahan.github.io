# Alex McClanahan

Personal site. Intended live URL: https://alexmcclanahan.github.io

This repository builds a static site with [Eleventy](https://www.11ty.dev/). A GitHub Action deploys from `master` or `main` after GitHub Pages is set to **GitHub Actions** as the source.

## Run locally

```
npm install
npm start
```

Then open http://localhost:8080

## Edit

- Add a post: copy `templates/YYYY-MM-DD-slug.md` to `src/writing/posts/YYYY-MM-DD-slug.md` (use a real date and slug) and fill in the title and body.
- Edit About: change `src/index.md`.
- Add a paper: add a list item in `src/research/index.md`.
