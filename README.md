# Garg Snack & Bakery — Static site

## How to publish on GitHub Pages

1. Create a new repository on GitHub (public is fine).
2. Copy all site files into the repo (index.html, CSS, JS, images/, site.webmanifest, sitemap.xml, robots.txt, favicon.*).
3. Commit and push to the `main` (or `master`) branch.
4. On GitHub: Settings → Pages → Source → choose `main` branch / root → Save.
5. After a minute, your site will be available at `https://<username>.github.io/<repo>/` or your custom domain (if CNAME present).
6. Submit the final URL and `/sitemap.xml` to Google Search Console.

Notes:
- Replace example URLs in `sitemap.xml` and `<head>` meta tags with your real domain.
- Make sure image links are relative (e.g. `/images/banner-garg.jpg`), not `D:\...`.
- GitHub Pages serves the site over HTTPS automatically.
