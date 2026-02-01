# SR Farrell Consultancy Website

Production-ready website for SR Farrell Consultancy - AI Automation & Content Strategy services.

## Quick Start

```bash
# Install a simple HTTP server (if not already installed)
npm install -g serve

# Serve the website locally
serve .

# Or use Python
python3 -m http.server 8000
```

Then open http://localhost:3000 (serve) or http://localhost:8000 (Python)

## Project Structure

```
├── css/
│   └── styles.css          # Main stylesheet
├── index.html              # Home page
├── services.html           # Services page
├── about.html              # About page
├── work.html               # Portfolio/case studies
├── contact.html            # Contact form (Netlify Forms)
├── success.html            # Form submission confirmation
├── 404.html                # Custom error page
├── favicon.svg             # SRF monogram logo
├── sitemap.xml             # SEO sitemap
├── robots.txt              # Search engine directives
├── netlify.toml            # Netlify configuration
└── _redirects              # URL redirects
```

## Deployment to Netlify

### Option 1: Git Integration (Recommended)
1. Push this folder to GitHub/GitLab/Bitbucket
2. Log in to [Netlify](https://netlify.com)
3. Click "Add new site" > "Import an existing project"
4. Connect your repository
5. Deploy settings are auto-configured via `netlify.toml`

### Option 2: Drag & Drop
1. Go to [Netlify Drop](https://app.netlify.com/drop)
2. Drag this entire folder onto the page
3. Site will be live instantly

### Post-Deployment Setup

1. **Custom Domain**: Site settings > Domain management > Add custom domain
2. **Form Notifications**: Site settings > Forms > Form notifications > Add email (srfarrellconsultancy@gmail.com)
3. **HTTPS**: Automatically enabled by Netlify

## Features

- **Responsive Design**: Mobile-first, works on all devices
- **Accessibility**: WCAG AA compliant (skip links, ARIA, focus states)
- **SEO Optimized**: Meta tags, Open Graph, structured data, sitemap
- **Performance**: Optimized CSS, lazy animations, caching headers
- **Contact Form**: Netlify Forms with spam protection

## Brand Colors

| Color | Hex | Usage |
|-------|-----|-------|
| Primary Blue | `#1E3A8A` | Logo, CTAs, hero backgrounds |
| Accent Cyan | `#06B6D4` | Highlights, labels, accents |
| Header Grey | `#9CA3AF` | Navigation background |
| Dark Grey | `#333333` | Body text, footer |

## Contact

- Email: srfarrellconsultancy@gmail.com
- Website: https://srfarrell.com

---

© 2025 SR Farrell Consultancy Ltd. Registered in Ireland.
