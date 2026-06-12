# JG Quality Carwash

Static Vercel site for JG Quality Carwash.

## Pages

- `index.html` is the public website.
- `admin.html` is the price editor.
- `data/prices.json` stores the public pricing menu.

## Vercel

Deploy from the `main` branch with no build command. The site is plain static HTML, CSS, and JavaScript.

The admin page updates `data/prices.json` through the GitHub API. Use a fine-grained GitHub token with repository contents read/write access for this repo. After publishing from admin, Vercel should redeploy from GitHub and the public pricing will update.
