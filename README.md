# Barcode Lab Website

Standalone support site for the Barcode Lab app.

- Domain: `barcodelab.app`
- App Store privacy URL: `https://barcodelab.app/privacy/`
- App Store support URL: `https://barcodelab.app/support/`
- Feedback URL: `https://barcodelab.app/feedback/`

## Structure

- `/index.html`
- `/privacy/index.html`
- `/support/index.html`
- `/feedback/index.html`
- `/assets/styles.css`
- `/CNAME`

## Publish to GitHub Pages

1. Create a new GitHub repository (example: `barcodelab-site`).
2. Push this folder to the repository `main` branch.
3. In GitHub repo settings, open `Pages` and set source to `Deploy from a branch` (`main` / root).
4. Confirm `CNAME` contains `barcodelab.app`.
5. Enable `Enforce HTTPS` in Pages settings once the certificate is issued.

## DNS for `barcodelab.app`

Use your domain registrar DNS panel:

- `A` record for `@` to GitHub Pages IPs:
  - `185.199.108.153`
  - `185.199.109.153`
  - `185.199.110.153`
  - `185.199.111.153`
- `CNAME` for `www` to:
  - `DigitalPhilately.github.io`

After DNS propagates, GitHub Pages should serve the site at `https://barcodelab.app`.
