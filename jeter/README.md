# HB 06 — Jeter Website

A standalone, responsive showcase website for Jeter. This is a **demonstration**, not a verified presentation of the business's actual services, location, credentials or contact information.

## What's included

- `index.html`: semantic, accessible single-page site
- `styles.css`: independent responsive styling, original CSS hero artwork
- `site.config.js`: first stop for future brand, about, services copy
- `script.js`: accessible mobile menu, config rendering, footer year
- `favicon.svg`: temporary original J mark

No build tools are required. Open `index.html` to preview locally or serve the entire directory as static files.

## Customize for Jeter

1. Confirm the actual business name, industry, services, contact details, service area, official logo, images and brand colors.
2. Replace generic sample text and services in `site.config.js` and the remaining HTML page sections.
3. Remove the demo banner **only after** all business content has been approved.
4. Add a verified contact mechanism (real mailto/tel targets or an explicitly configured and tested form).
5. The web intake portal is a separate project and is intentionally *not* implemented here. After delivery, verify its URL/API and integrate by link/embedding as appropriate.

## Deployment

The source can be committed into a separate customer repository and connected to Cloudflare Pages. For a static project, set the build command to empty and output directory to `/` (root). Do not change the existing ShanX site, live domain DNS or hosting without matching approvals. Create a project-specific preview URL first and verify on desktop and mobile.

## Tests

- No hardcoded unverified phone, email, address, service area or testimonials.
- Mobile nav opens/closes with mouse, touch, keyboard and Escape.
- Links are in-page navigation or clearly indicated placeholders.
- The footer year updates at runtime.
- The website is independent of all intake-app code.
- Check reduced motion and narrow viewport behavior before delivery.

## Workstation policy

Mom's PC is the intended website-building workstation, accessed through authorized GREMLIN DIRECT → RustDesk. Keep Roku Launchpad and unrelated customer work untouched. Verify the actual target desktop and file location before writing there. No dedicated Mom PC connector is presumed.