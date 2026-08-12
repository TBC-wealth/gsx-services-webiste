# GSX Services

Static website for **GSX Services FZCO** (Dubai, UAE), served via GitHub Pages at [gsxservices.com](https://gsxservices.com).

## Structure

```
├── index.html          # Landing page
├── assets/
│   ├── css/style.css   # Styles
│   └── js/main.js      # Interactions (nav, scroll animations)
├── CNAME               # Custom domain
├── .github/workflows/  # GitHub Actions (Pages deploy)
└── README.md
```

## Development

Open `index.html` in a browser to preview locally — no build step required.

## Deploy

Pushing to `main` triggers the GitHub Actions workflow, which publishes the site to GitHub Pages automatically.
