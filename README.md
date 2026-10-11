# Dhruvision Website

A responsive static marketing website for Dhruvision, an early-stage Server-Driven UI product initiative.

## Files
- `index.html` — main landing page
- `styles.css` — responsive styles
- `script.js` — mobile navigation, reveal animations, and current year
- `privacy.html` — starter privacy notice; review before publishing
- `assets/logo.svg`, `assets/favicon.svg` — brand assets

## Run locally
Open `index.html` in a browser, or start a simple local server from this directory:
```bash
python -m http.server 8000
```
Then visit `http://localhost:8000`.

## Deploy
This is a static site. You can deploy the folder to a static hosting provider such as Vercel, Netlify, or GitHub Pages. Configure `dhruvision.space` and optionally `www.dhruvision.space` in the hosting provider's domain settings.

**Important DNS note:** keep your existing Zoho Mail MX records and email-related TXT records (SPF, DKIM, DMARC) when configuring website hosting. Add or change only the website records requested by your hosting provider. Do not replace all DNS records blindly.

## Before publishing
1. Verify that `ceo@dhruvision.space` can send and receive email.
2. Confirm SPF and DKIM status in Zoho Mail; consider adding DMARC once those are correct.
3. Review the privacy notice against your real practices and applicable legal requirements.
4. Add a real postal/company address only if appropriate and accurate; none has been invented here.
5. Replace or supplement the concept illustration if you have actual product screenshots.
6. Keep product claims accurate. This site describes Dhruvision as in development and labels roadmap items as planned or exploring.
7. Check the current Claude Startups programme requirements directly before applying; a website does not guarantee acceptance.

## Design
Dark navy and violet/blue visual system, responsive layout, mobile menu, keyboard skip link, reduced-motion support, and a conceptual UI illustration built with HTML/CSS (no stock image dependency).
