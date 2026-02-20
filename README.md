# TechShift Insights Hub (Netlify Project)

This is a static, Netlify-ready landing page inspired by the structure of `techshift.io`, with original copy and styling.

## Project files

- `index.html` – main page
- `styles.css` – styles
- `netlify.toml` – Netlify configuration

## Deploy to Netlify

### Option 1: Netlify UI (recommended)

1. Create a new site in Netlify from your GitHub repository.
2. Build command: *(leave blank)*
3. Publish directory: `.`
4. Deploy.

### Option 2: Netlify CLI

```bash
npm i -g netlify-cli
netlify login
netlify init
netlify deploy --prod --dir .
```
