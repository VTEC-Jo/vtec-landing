# VTEC Landing Page

A production-ready, high-signal static landing page for VTEC, a technology company specializing in robotics, AI, and industrial expertise in Jordan.

## Features

- **Multi-Page Structure**: Separate landing, partner, and workshop pages for focused user journeys.
- **Google Apps Script Integration**: Form submissions to Google Sheets for easy lead management.
- **WCAG 2.1 AA Accessible**: Keyboard navigation, screen reader support, and ARIA attributes.
- **SEO Optimized**: robots.txt, sitemap.xml, canonical URLs, and Open Graph images.
- **Dark Mode Support**: Respects system preferences and includes a manual toggle with persistence.
- **Performance Optimized**: No heavy frameworks or dependencies; fast loading via static HTML/CSS/JS.
- **GitHub Pages Ready**: Simple file structure with relative paths for easy hosting.

## Project Structure

```text
vtec-landing/
├── assets/
│   ├── favicon.svg          # Brand favicon
│   └── og-image.png         # Social media preview image
├── index.html               # Main landing page
├── partner.html             # Partnership inquiry page
├── workshops.html           # Workshop catalog & registration
├── style.css                # Design system & responsive styles
├── script.js                # Interactive components (nav, theme, forms)
├── robots.txt               # Search engine crawl instructions
├── sitemap.xml              # SEO sitemap for search engines
└── CHANGELOG.md             # Version history & changes
```

## Site Structure

This is a multi-page static site with three main entry points:

1. **index.html** - Main landing page with company overview, services, and contact form.
2. **partner.html** - Partnership inquiry page with detailed organization form.
3. **workshops.html** - Workshop catalog with registration form and program details.

All forms submit to Google Apps Script endpoints that store data in Google Sheets.

## SEO & Search Engine Optimization

The site includes comprehensive SEO infrastructure:
- **robots.txt**: Search engine crawl instructions pointing to sitemap.
- **sitemap.xml**: XML sitemap listing all pages with priorities and update frequencies.
- **Canonical URLs**: Prevents duplicate content issues across all pages.
- **Open Graph Image**: 1200×630 social media preview image for LinkedIn/Twitter shares.
- **Semantic HTML**: Proper heading hierarchy and structured data ready for rich snippets.

## Accessibility (WCAG Compliant)

The site meets WCAG 2.1 AA standards:
- **Keyboard Navigation**: Visible focus indicators on all interactive elements.
- **Screen Reader Support**: ARIA labels, live regions for form feedback, and aria-required attributes.
- **Theme Toggle**: aria-pressed state for dark/light mode button.
- **High Contrast**: Color contrast ratios meet AA standards.
- **Semantic Structure**: Proper heading hierarchy and landmark regions.

## Self-Hosting on GitHub Pages

Follow these steps to deploy this site to GitHub Pages:

### 1. Create a New Repository
1. Log in to your GitHub account.
2. Click the **+** icon in the top right and select **New repository**.
3. Name your repository (e.g., `vtec-landing`).
4. Set it to **Public** (or Private if you have a Pro account, though Public is standard for landing pages).
5. Click **Create repository**.

### 2. Upload the Files
1. On your new repository page, click **uploading an existing file**.
2. Drag and drop all files from the `vtec-landing` folder (including `assets/`, `robots.txt`, `sitemap.xml`, `partner.html`, and `workshops.html`) into the upload area.
3. Add a commit message like "Initial landing page upload".
4. Click **Commit changes**.

### 3. Enable GitHub Pages
1. Go to the **Settings** tab of your repository.
2. In the left sidebar, under "Code and automation", click **Pages**.
3. Under "Build and deployment" > "Branch", ensure **main** (or `master`) is selected and the folder is set to **/(root)**.
4. Click **Save**.
5. Wait a minute or two. GitHub will provide a URL like `https://yourusername.github.io/vtec-landing/`.

### 4. Custom Domain (Optional)
If you have a custom domain (e.g., `vtec.jo`):
1. In the **Pages** settings, scroll down to **Custom domain**.
2. Enter your domain and click **Save**.
3. Update your DNS settings with your domain provider (GitHub provides instructions for this).

## Customization

- **Forms**: Configured for Google Apps Script integration. You'll need to create your own Apps Script web app and update the URLs in `script.js`.
- **SEO**: Update placeholder domain (`vtec.example.com`) in meta tags, `robots.txt`, and `sitemap.xml` with your real domain.
- **Colors**: You can easily change the primary accent color by updating the `--accent` variable in `style.css`.
- **Images**: Place any additional images in the `assets/` folder and use relative paths (e.g., `assets/your-image.jpg`).

## Changelog

See [CHANGELOG.md](CHANGELOG.md) for version history. This project follows [Semantic Versioning](https://semver.org/).

Current version: 1.2.0
- Latest: SEO infrastructure (robots.txt, sitemap, canonical URLs)
- Latest: Accessibility enhancements (WCAG 2.1 AA compliance)

## License

&copy; 2026 VTEC. All rights reserved.
