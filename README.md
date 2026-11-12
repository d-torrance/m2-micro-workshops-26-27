# Macaulay2 Micro-Workshops, 2026–27

Source for <https://d-torrance.github.io/m2-micro-workshops-26-27>.

A [Jekyll](https://jekyllrb.com) site using
[beautiful-jekyll](https://github.com/daattali/beautiful-jekyll) as a remote theme,
published by GitHub Pages from the `main` branch.

## Adding a workshop

Create a file in `_workshops/`, e.g. `03-cornell.md`:

```yaml
---
title: "Micro-Workshop III: Numerical Algebraic Geometry"
order: 3
date_display: "March 6–8, 2027"
location: "Ithaca, NY"
host: "Cornell University"
registration: "https://example.com/form"
blurb: "One or two sentences shown in the list on the home page."
---
```

The body is ordinary Markdown. The home page lists workshops sorted by `order`, and
each file gets its own page at `/workshops/<filename>/`.

## Local preview

```
bundle install
bundle exec jekyll serve
```

Then open <http://localhost:4000/m2-micro-workshops-26-27/>.

## Layout

- `_config.yml` — site settings, navbar, colors
- `index.md` — home page, workshop list, and organizers
- `code-of-conduct.md` — code of conduct, adapted from the Contributor Covenant 3.0
- `_workshops/` — one file per workshop
- `_layouts/workshop.html` — workshop page layout
- `assets/css/custom.css` — typography and card styling
