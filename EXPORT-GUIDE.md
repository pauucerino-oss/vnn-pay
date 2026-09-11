# VNN Pay — Source export

Marketing website for Vietnam-based businesses building a digital presence in the United States.

## Run and build

Requires Node.js >=22.13 and npm.

```sh
npm ci
npm run dev
# Production build and local production server:
npm run build
npm run start
```

Open the URL printed by the server. This vinext / React / TypeScript app needs a compatible runtime; it is not a static GitHub Pages export. Publishing source to GitHub does not deploy the site or connect vnnpay.org.

## Included pages

Landing page `/`, `/privacy`, `/refund`, `/security`, `/terms`, `/compliance`, `/sitemap`, and `/sitemap.xml`.

## Files

`app/` contains pages, styling and metadata; `public/` contains assets. Keep `build/`: it contains required Vite integration source, not generated output. `worker/` is the server entry. Database folders and examples are optional scaffolding. The original README and tests are inherited from the starter; the tests are not a verified VNN Pay acceptance suite.

## Launch limitations

This is a marketing prototype, not live payment processing or merchant onboarding. Dashboard examples are illustrative. Verify contact email ownership, business details and service scope before launch. Policy pages are drafts requiring review against actual operations; they do not establish licensing, certification or compliance. Sites configuration does not transfer hosting ownership or grant deployment access.

## Archive contents

Source snapshot: be6c3b49a5cd6304206bfc801403af9cb01dc980, plus this guide. Includes source, assets, lockfile and configuration. Excludes Git history, dependencies, environment files, build output and caches. No open-source license is granted by this archive.
