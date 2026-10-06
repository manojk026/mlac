# MLAC Techs — Official Website

You have **full ownership** of this website. All source is in this folder.

## Files
- `index.html` — the complete website (single file, ready to open or deploy)

## Security measures already applied
- Content-Security-Policy (restricts scripts, styles, images to trusted sources)
- X-Content-Type-Options: nosniff
- X-Frame-Options: SAMEORIGIN (prevents clickjacking)
- Referrer-Policy: strict-origin-when-cross-origin
- Permissions-Policy (disables camera, mic, geolocation)
- No backend / no database / no user data collection (static site = smaller attack surface)
- External resources limited to: Tailwind CDN, Google Fonts, Unsplash images

## Important
This is currently a **static** website. There is:
- No admin login
- No database
- No server-side code
- No forms that store data

“Best security” for a static marketing site = HTTPS + security headers + minimal third-party scripts (already done).

## How to get full control + public link
1. Download / copy the `index.html` file
2. Deploy free on:
   - **Netlify** (drag & drop the file) → free HTTPS
   - **Vercel**
   - **GitHub Pages**
   - **Cloudflare Pages**

Once deployed you get a public URL (e.g. `https://mlactechs.netlify.app`) and full control.

## How to edit
Just open `index.html` in any code editor (VS Code, Cursor, etc.) and change text, colors, sections, etc.

## Contact email currently set to
`mlac2k26@gmail.com`
