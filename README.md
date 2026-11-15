# PeWoNu landing page

Static site, no build step and no dependencies: `index.html` plus `img/`. English and Spanish (button in the header; it follows the browser language the first time).

Preview locally: `python -m http.server 8700` in this folder, then open http://127.0.0.1:8700.

Deploy: upload the whole folder to any static host (Cloudflare Pages, Netlify, GitHub Pages, nginx) and point the subdomain at it. The install commands point to the `develop` branch of https://github.com/MrT-coder/pewonu, so they work only after that branch is pushed.
