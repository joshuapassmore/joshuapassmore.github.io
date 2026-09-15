# Joshua Passmore

This repository contains the source for [joshuapassmore.org](https://joshuapassmore.org/), a Jekyll website hosted with GitHub Pages.

## Local preview

Install Ruby and Bundler, then run:

```sh
bundle install
bundle exec jekyll serve
```

Open `http://localhost:4000` in a browser.

## Publishing

GitHub Pages builds and deploys changes to `main` automatically. Keep `CNAME`
set to `joshuapassmore.org` and the `url` in `_config.yml` set to
`https://joshuapassmore.org`.

## Posts and PDFs

Create posts in `_posts` using a `YYYY-MM-DD-title.md` filename and front matter:

```yaml
---
layout: post
title: "My post title"
date: 2026-09-15
---
```

The homepage lists the five most recent published posts. Future-dated posts
appear only after a build on or after their publication date, in the site's
`Africa/Johannesburg` timezone.

Upload PDFs to `assets/` and link to them from a page or post, for example:

```liquid
[MSc thesis (PDF)]({{ '/assets/msc-thesis.pdf' | relative_url }})
```

## Mathematics

Write inline mathematics as `$x^2$` and displayed mathematics as `$$x^2$$`.
MathJax loads automatically when rendered content or headings contain math
markers; ordinary text pages do not download it. No front-matter setting is
needed for equations. Existing TeX and MathML support and the deferred loader
are retained.

For a page that adds equations dynamically with JavaScript, use `math: true`
in its front matter and call `MathJax.typesetPromise()` after adding them once
MathJax is ready. To force MathJax on every page, set `math: true` in
`_config.yml`.

## Shared footer

`_layouts/default.html` contains the contact address and the last-updated line.
The timestamp is the latest site build time, displayed in SAST. Keep the email
address in its obfuscated form; do not add a `mailto:` link.
