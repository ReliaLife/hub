# hub

A simple public launcher page for ReliaLife's web tools, served via GitHub Pages.

## Editing

Everything lives in [`index.html`](./index.html) — a single self-contained page (inline CSS, no build step). To add a tool, copy one of the `<a class="card">` blocks and update the href, title, description, and badge. See the comment in the file for a template, including the "Coming soon" variant for tools that aren't live yet.

## Tools currently listed

- **RefineryRBD** — https://refinery-rbd.vercel.app/
- **Weatherstation Höf** — https://weather.relialife.app/

## Deployment

Pushes to `main` are published by GitHub Pages (source: deploy from `main` / root).
