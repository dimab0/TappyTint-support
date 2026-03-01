# TappyTint Support Site

This repo hosts the public support/legal pages for Tappy Tint via GitHub Pages.

## Public pages

- `/support.html` (App Store Support URL)
- `/privacy-policy.html` (App Store Privacy Policy URL)
- `/terms-and-conditions.html`
- `/data-deletion.html`

## GitHub Pages

Deployment is automated by `.github/workflows/pages.yml` on every push to `main`.

After first push:

1. Go to repo **Settings -> Pages**.
2. Set **Source** to **GitHub Actions**.
3. Wait for the workflow run named `Deploy GitHub Pages` to complete.

Expected site URL:

- `https://dimab0.github.io/TappyTint-support/`

Submit these to App Store Connect:

- Support URL: `https://dimab0.github.io/TappyTint-support/support.html`
- Privacy Policy URL: `https://dimab0.github.io/TappyTint-support/privacy-policy.html`
