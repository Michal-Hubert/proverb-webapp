# Random Proverb

A tiny web app that shows a random proverb.

## Run locally

```
npm install
npm start
```

Then open http://localhost:3000 in your browser.

## Deployment notes

This is a static web app (one HTML file with inline CSS and JavaScript) served by `serve`, a small Node.js static file server. There is no backend API, no database, and no build step.

A hosting platform needs:

- **Node.js** (18 or later)
- **Install command:** `npm install`
- **Start command:** `npm start`
- **Port:** `serve` listens on port 3000 by default; set the `PORT` environment variable to override

Alternatively, since this is purely static, you can skip the Node server entirely and deploy `index.html` to any static host (GitHub Pages, Netlify, etc.).
