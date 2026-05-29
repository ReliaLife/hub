# hub

A simple public launcher page for ReliaLife's web tools, served via GitHub Pages.

## Editing

Everything lives in [`index.html`](./index.html) — a single self-contained page (inline CSS + a few lines of vanilla JS, no build step).

Layout is master/detail: a list of tool buttons on the left, a description panel on the right. To add a tool:

1. Add a `<button class="tool-btn" data-target="yourid">` to `<nav class="toollist">` (set `data-target` to a unique id).
2. Add a matching `<article class="panel" id="yourid">` in `<div class="detail">` with the heading, description, "Who it's for", and an `<a class="openbtn">` link.

Clicking a button shows its panel (handled by the script at the bottom). Deep links work too, e.g. `tools.relialife.app/#weatherstation`.

## Tools currently listed

- **RefineryRBD** — https://refinery-rbd.vercel.app/
- **Weatherstation Höf** — https://weather.relialife.app/

## Deployment

Pushes to `main` are published by GitHub Pages (source: deploy from `main` / root).
