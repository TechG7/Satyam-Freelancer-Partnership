SATYAM KUMAR – FREELANCER & PARTNERSHIP PWA

GitHub Pages-ready responsive PWA website.

PHOTO WORKFLOW
1. Add JPG/PNG/JPEG/BMP/TIFF images to the assets/ folder in GitHub.
2. Push/commit the change to main or master.
3. GitHub Actions -> Optimize Images & Update Gallery runs automatically.
4. The action converts supported raster images to optimized WebP, removes the original raster file, and regenerates gallery-data.js.
5. The website automatically shows the new WebP image.

IMPORTANT
- Do not add the same image in both JPG/PNG and WebP unless you intentionally want duplicates.
- SVG files are not converted by this workflow.
- The workflow needs Actions enabled and repository contents write permission (the workflow declares it).
- GitHub Pages should serve the site over HTTPS for full PWA functionality.
