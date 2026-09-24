# Rutva Safi — Portfolio

A responsive, single-page portfolio for senior technical writer Rutva Safi. Built with semantic HTML, CSS, and a small JavaScript enhancement for mobile navigation. No build step or application dependencies.

Live site: https://crove4n.github.io/Rutva-page/

## Local preview

From this directory, run `python -m http.server 4173 --bind 127.0.0.1`, then open http://127.0.0.1:4173. Stop the server with Ctrl+C. The page also works when opened directly from disk.

## Editing

- `index.html`: biography, selected work, public appearances, use cases, podcasts, recognition, and contact links.
- `styles.css`: colors, typography, responsive layouts, and reduced-motion support.
- `DESIGN.md`: white and royal-purple palette, token roles, and contrast pairs.
- `script.js`: mobile menu, Escape dismissal, and focus handling.
- `assets/`: the CV-sourced portrait, podcast and article thumbnails, and custom favicon.

The page uses DM Sans and Instrument Serif from Google Fonts, with system fallbacks. All other assets are local. Content and navigation remain available without JavaScript.

## Content rules

Career information is based on Rutva's September 19, 2026 CV. Employer documentation is summarized rather than reproduced. The use cases restate work already described on the page and do not claim specific outcomes. Podcast, webinar, conference, recognition, Crowdin blog, and LinkedIn destinations come from the CV or the supplied URLs; podcast titles were verified against YouTube's public metadata. Podcast thumbnails are local copies of the corresponding YouTube thumbnails and link to the original videos.

The "Out in the world" section features the tcworld conference session, WomenTech Global Awards nomination, and Crowdin blog interview. Its local thumbnails are copies of the public speaker portrait from the tcworld session page, official nominee graphic from the WomenTech page, and article hero from the Crowdin page, respectively. The WomenTech and Crowdin graphics use a CSS display crop to keep their lower employer text out of view; the source images are unedited. "On the mic" features the Document360 podcast and webinar, plus a separate link to the WomenTech nomination. LinkedIn restricts automated visits; its URL matches the supplied CV. Do not add unsupported results, testimonials, or availability claims.

Only Rutva's email and LinkedIn are offered as contact methods. Do not commit the source CV, reference details, phone numbers, or temporary inspection files. There is no CV download, analytics, contact form, or public deployment configuration.

## Verification

Check the page at mobile, tablet, and desktop sizes; keyboard navigation, menu open/close and Escape behavior; anchor links and external links; 200% zoom; reduced motion; and the no-JavaScript fallback. Confirm no horizontal overflow, missing assets, or browser console errors before publishing changes.

Verified in Chromium on September 20, 2026 at 320, 390, 620, 768, 1024, and 1440 CSS pixels, plus 200% text sizing and the effective viewport for 200% zoom. Mobile menu keyboard navigation, Escape focus return, link dismissal, breakpoint reset, reduced motion, and JavaScript-disabled navigation passed. No horizontal overflow, local asset failures, or page script errors were found. Primary text/background contrast pairs exceed 4.5:1. HTML nesting, anchor targets, and the contact-data audit also passed. Screenshots and temporary checks are kept outside the tracked source.
