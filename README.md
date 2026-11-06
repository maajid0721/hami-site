# HAMI Tech Labs website

Responsive static corporate and product website for HAMI Tech Labs, hosted with GitHub Pages at `hamiapp.in`.

## Site structure
- `index.html` — HAMI Tech Labs corporate homepage and product directory
- `hami-app.html` — HAMI App product description and policy links
- `hami-fit.html` — HAMI FIT product description and policy links
- `privacy.html` — common Privacy Policy with product-specific schedules
- `terms.html` — common Terms & Conditions with product-specific sections
- `billing.html` — common billing, cancellation and refund framework
- `cookies.html` — Cookie & Tracking Notice
- `styles.css` — shared responsive styling
- `script.js` — mobile navigation and footer year
- `assets/favicon.svg` — site icon
- `CNAME` — custom domain

## Publish with GitHub Pages
1. Open **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**, branch `main`, folder `/ (root)`.
3. Keep the custom domain `hamiapp.in` and existing DNS configuration.
4. Preserve existing MX, SPF, DKIM and DMARC records used by email.
5. Enable **Enforce HTTPS** after GitHub Pages issues the certificate.

## Before public release
- Confirm the legal operator name, legal status and official postal address.
- Have the common policies and product-specific schedules reviewed by an Indian technology/privacy lawyer.
- Verify HAMI App and HAMI FIT live data flows, payment providers, refund rules, retention periods and deletion processes.
- Do not describe roadmap features as live features.
- If analytics, advertising pixels or other tracking tools are added, update the Cookie & Tracking Notice and consent controls as required.

The legal pages in this repository are working drafts and must be reconciled with actual product operations before publication.
