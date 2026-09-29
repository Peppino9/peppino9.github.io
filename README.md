# Simon Gorny, portfolio

A static site: `index.html`, an `img` folder and a favicon. No build step.

## Before you publish
1. Open `index.html` and replace `YOUR-SITE-URL` in the `og:image` line with the real address (for example `https://simongorny.se`). Social previews need a full address.

## GitHub Pages
1. Create a repository on GitHub (for example `portfolio`) and upload everything in this folder.
2. Settings, Pages, Source: "Deploy from a branch", branch `main`, folder `/ (root)`.
3. The site appears at `https://<username>.github.io/<repository>/`.

## Cloudflare Pages
1. Workers and Pages, Create, Pages, Upload assets (or connect the repository).
2. Framework preset "None", no build command, output directory `/`.
3. Add a custom domain under Custom domains if you have one.
