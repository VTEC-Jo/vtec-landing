# VTEC Landing Page

A production-ready, high-signal static landing page for VTEC, a technology company specializing in robotics, AI, and industrial expertise in Jordan.

## Features

- **Clean & Editorial Design**: A modern, grid-based layout that avoids generic AI startup clichés.
- **Fully Responsive**: Optimized for desktop, tablet, and mobile devices.
- **Dark Mode Support**: Respects system preferences and includes a manual toggle with persistence.
- **Performance Optimized**: No heavy frameworks or dependencies; fast loading via static HTML/CSS/JS.
- **SEO Ready**: Semantic HTML, meta tags, and Open Graph support for social sharing.
- **Accessibility Focused**: High contrast, keyboard navigation support, and semantic markup.
- **GitHub Pages Ready**: Simple file structure with relative paths for easy hosting.

## Project Structure

```text
vtec-landing/
├── assets/
│   └── favicon.svg     # Brand favicon
├── index.html          # Main page structure & content
├── style.css           # Design system & responsive styles
├── script.js           # Interactive components (nav, theme, form)
└── README.md           # Documentation
```

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
2. Drag and drop all files from the `vtec-landing` folder (including the `assets` folder) into the upload area.
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

- **Contact Form**: The form is pre-configured for [Formspree](https://formspree.io/). To make it work, create a free account, get your Form ID, and replace `YOUR_FORM_ID` in the `index.html` file's form action.
- **Colors**: You can easily change the primary accent color by updating the `--accent` variable in `style.css`.
- **Images**: Place any additional images in the `assets/` folder and use relative paths (e.g., `assets/your-image.jpg`).

## License

&copy; 2026 VTEC. All rights reserved.
