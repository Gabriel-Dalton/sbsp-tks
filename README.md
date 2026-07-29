# Space Based Solar Power

A static site explaining space based solar power, built in 2024 for a TKS project. Five pages: the landing page, an explainer, a CAD model, a physical model, and a page on how the site itself was kept light.

## Contents

- `index.html`, `what-is-sbsp.html`, `CAD-Model.html`, `Physical-Model.html`, `sustainability.html`
- `min.css`, a trimmed Tailwind build
- Both model write ups as PDFs, with the renders and photos used on the pages
- `video_script.txt` and the presentation script that went with the project

Alpine.js loaded from a CDN handles the mobile menu and the dismissible notice in the corner. Nothing else runs on the page and there is no build step.

## The old domain

The site was served at sbsp.oasisofchange.org. That name now returns a 301 to oasisofchange.com, so the pages are not live there any more.

Every page links its stylesheet by absolute URL to the old host, so opening a file from disk gives unstyled HTML. Point the `link` tag at the local `min.css` to see a page as it looked.
