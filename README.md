# Open Science · Education · Creative Tools

A free, static website that curates high-quality open science, education, and creative tools.

Designed to be useful for both humans and AI agents (semantic HTML, JSON feed, llms.txt, robots.txt).

## Files
- `index.html` – main page
- `styles.css` – dark, clean styling
- `data.json` – machine-readable list of all resources
- `llms.txt` – summary for AI agents
- `robots.txt` – allows respectful crawlers
- `sitemap.xml` – for search engines

## Deploy for free

### Option 1: GitHub Pages (easiest for most people)
1. Create a new GitHub repository (public) named e.g. `open-science-edu-creative`
2. Upload all files from this folder to the repository (or push via git)
3. Go to **Settings → Pages**
4. Under “Source” choose **Deploy from a branch** → `main` (or `master`) → `/ (root)`
5. Save. Your site will be live at:  
   `https://YOUR-USERNAME.github.io/open-science-edu-creative/`

Replace `YOUR-USERNAME` in the HTML, robots.txt and sitemap.xml if you want perfect links (optional).

### Option 2: Cloudflare Pages (unlimited bandwidth, recommended for traffic)
1. Go to [https://pages.cloudflare.com](https://pages.cloudflare.com) and sign in (free account)
2. Create a new project → Connect to Git (or direct upload)
3. Upload the folder or connect the GitHub repo
4. Build settings: Framework preset = None, Build command = empty, Output directory = `/`
5. Deploy. You get a `*.pages.dev` URL instantly. Custom domain is free later.

## Customization
- Edit `index.html` to add/remove resources
- Update `data.json` and `llms.txt` to keep the AI-friendly versions in sync
- Change colors in `styles.css` (`:root` variables)

## License
This directory is free to use, copy, and host. Individual linked sites keep their own licenses.
