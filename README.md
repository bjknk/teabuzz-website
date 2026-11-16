# TeaBuzz Website

A responsive, animated marketing website for TeaBuzz.

## Files
- `index.html` — page structure and content
- `style.css` — responsive design, layout and animations
- `script.js` — mobile navigation and scroll reveal
- `assets/` — supplied TeaBuzz logo, app screenshots and founder photo (including optimised WebP copies)

## Deploy with Cloudflare Pages
1. Create a public GitHub repository named `teabuzz-website`.
2. Upload the contents of this folder to the repository root (not the enclosing folder).
3. In Cloudflare, open **Workers & Pages → Create application → Pages → Connect to Git**.
4. Select this repository.
5. Framework preset: **None**. Build command: leave blank. Build output directory: `/`.
6. Deploy.
7. Add `teabuzz.org` under the project's **Custom domains** after the project is deployed.

The site uses no paid libraries or backend. Google Fonts and one campus lifestyle photo load from external services; the app screenshots, logo and founder photo are stored locally in `assets/`.

## Before publishing
- Review the founder story wording and confirm the founder photo is approved for public use.
- Add official TikTok, Facebook and YouTube links when available.
- Add a link to the current TeaBuzz Privacy Policy and Terms of Use if you want these linked in the footer.
- The App Store URL supplied is used as provided.
