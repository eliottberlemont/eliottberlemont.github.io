# Engineering portfolio

Personal portfolio site — rocket avionics, data acquisition, and flight systems work
with UMBRA at Cal Poly Pomona, plus personal high-power rocketry projects.

Static HTML and CSS, no build step. `index.html` is the whole site; `styles.css` holds
the design system; photos live in `assets/img/`.

## Running it locally

Open `index.html` in a browser, or serve the folder:

```
python3 -m http.server 8000
```

## Publishing

This repo is set up for GitHub Pages. For a user site the repo must be named
`<your-username>.github.io`, and Pages should be set to deploy from the `main` branch,
root folder, under Settings → Pages.

`.nojekyll` is present so GitHub serves the files as-is rather than running them
through Jekyll.

## Editing

Each project is a `<section class="project">` in `index.html`. To add one, copy an
existing section, change the `id`, and update the heading, role line, prose, and the
`<dl class="specs">` block.
