# Acme Consulting — Netlify Starter

This is a minimal, production-ready static site configured for Netlify hosting, Netlify Forms, SEO, and a newsletter embed.

## Quick Start
1. Zip and upload this folder to Netlify (or connect a GitHub repo with these files).
2. In Netlify, enable **Forms** (it will auto-detect the `contact` form on first submission).
3. Replace `example.com` with your real domain in:
   - `index.html` (`canonical`, `og:url`, `og:image`), JSON-LD, and any links
   - `robots.txt` (Sitemap URL)
   - `sitemap.xml` (loc entries)
   - `netlify.toml` (`baseUrl`)
4. Add your **Mailchimp** (or other) newsletter form `action` URL in `index.html`.
5. (Optional) Add your **GA4** Measurement ID in `index.html` and uncomment the GA script.
6. Deploy!

## Netlify Forms
- The contact form uses `data-netlify="true"` and a hidden `form-name` input.
- A honeypot `bot-field` is included to reduce spam.
- Configure email notifications under **Site settings → Forms → Notifications**.

## Domain
- Start on your-site-name.netlify.app.
- When you own a domain (Namecheap/Cloudflare/Google Domains), add it under **Domain settings → Add custom domain** and follow the DNS prompts.
- Update canonical/meta tags and `netlify.toml` once live.

## SEO
- Title + meta description in `<head>`.
- Open Graph / Twitter tags for rich sharing.
- `robots.txt` and `sitemap.xml` included; plugin keeps sitemap updated on build.

## Local Edits
Open `index.html` and `styles.css` to customize copy and design.
