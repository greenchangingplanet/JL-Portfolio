# JL-Portfolio — static contact page

This repository contains a simplified static contact page adapted from a WordPress export.

What I added:

- kontakt-julia-lew.html — simplified contact page (static HTML) that references styles and images in /assets
- assets/styles.css — extracted minimal stylesheet

What you need to do next:

1. Upload images to /assets in this repository (file names expected below):
   - Logo-glowne-300x300.png
   - Simple-logo-lew.png

2. Enable GitHub Pages (optional) to serve the site:
   - Go to the repository Settings → Pages
   - Choose the default branch and the root (/)
   - Save. The site will be available at https://<your-username>.github.io/JL-Portfolio/ (replace with your Pages domain if configured)

3. After enabling Pages, if you want social previews to show the correct absolute URL, update the og:url meta tag in kontakt-julia-lew.html to the published URL.

Notes:
- This commit intentionally strips WordPress-specific scripts, inline styles, and plugin metadata. If you need any of those restored (schema.org JSON-LD, feeds, navigation), tell me which pieces and I will add them back minimally.
