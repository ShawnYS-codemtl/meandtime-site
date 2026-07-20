# meandtime-site

The public website for **me and time** — a private iOS diary for watching your own face
change over time. This repo exists to host the app's **Privacy Policy** and **Support** pages
(required by the App Store) plus a small landing page. It contains no app source code; the app
itself lives in a separate private repository.

## Pages

| File | Purpose |
| --- | --- |
| `index.html` | Landing page — app icon, tagline, and links to the two pages below. |
| `privacy.html` | Privacy policy. Linked from App Store Connect and from inside the app (paywall + Settings). |
| `support.html` | Support / help page with contact info and an FAQ. |
| `icon.png` | App icon, used by the landing page. |

The pages are self-contained: plain HTML with inline CSS, no build step, no external scripts,
fonts, or trackers.

## Live site

Published with **GitHub Pages** at:

- <https://shawnys-codemtl.github.io/meandtime-site/>
- <https://shawnys-codemtl.github.io/meandtime-site/privacy.html>
- <https://shawnys-codemtl.github.io/meandtime-site/support.html>

## Publishing

Pages serves this repo's `main` branch from the root:

1. **Settings → Pages**
2. **Source:** *Deploy from a branch*
3. **Branch:** `main`, folder `/ (root)`

The repo must be **public** for GitHub Pages to publish on the free plan. Changes go live a
minute or so after each push to `main`.

## Editing locally

No tooling required — open any page directly in a browser:

```sh
open index.html
```

Edit the HTML/CSS and refresh the browser to preview.

## Contact

Questions or support: [shawnyatsin.dev@gmail.com](mailto:shawnyatsin.dev@gmail.com)
