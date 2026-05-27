# David Zdravkovic — Personal Website

Static portfolio and technical blog. No build step — open `index.html` in a browser, or serve the folder over HTTP.

## Structure

```
├── index.html
├── styles.css
├── images/
├── posts/
│   ├── chat-views-and-storage.html
│   └── message-ordering.html
└── README.md
```

## Local preview

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## GitHub Pages

1. Push this repo to GitHub (see below).
2. In the repo: **Settings → Pages → Build and deployment → Source**: deploy from branch `main`, folder `/ (root)`.
3. Your site will be at `https://davidzdravkovic.github.io/<repo-name>/` (or `https://davidzdravkovic.github.io/` if the repo is named `davidzdravkovic.github.io`).

## Push to GitHub

From this folder:

```bash
git remote add origin https://github.com/davidzdravkovic/davidzdravkovic.github.io.git
git push -u origin main
```

Create an empty repository named `davidzdravkovic.github.io` on GitHub first if it does not exist yet (**do not** add a README when creating it).
