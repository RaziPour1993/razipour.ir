# Mohammad Razipour | iOS Engineer

Personal CV/Resume website built with plain HTML & CSS.

**Live Site:** [razipour.ir](https://razipour.ir/)

## Setup

### GitHub Pages
1. Push this repo to GitHub
2. Go to Settings > Pages
3. Set source to "Deploy from a branch"
4. Select `main` branch and `/ (root)` folder
5. Click Save

### Cloudflare DNS
1. Add your domain to Cloudflare
2. Set DNS records:
   - Type: `CNAME`, Name: `@`, Target: `razipour1993.github.io`
3. Enable SSL/TLS (Full mode)

## Update Content

Edit `index.html` to update:
- Work experience
- Skills
- Translated books
- Contact information

Edit `style.css` to customize colors and layout.

## Structure

```
├── index.html      # Main CV page
├── style.css       # Styles
├── CNAME           # Custom domain config
├── .nojekyll       # Disable Jekyll processing
└── README.md       # This file
```
