# Rutva Safi — Portfolio

A responsive, single-page portfolio for senior technical writer Rutva Safi. Built with semantic HTML, CSS, and a small JavaScript enhancement for mobile navigation. No build step or application dependencies.

Live site: https://crove4n.github.io/Rutva-page/

## Local preview

From this directory, run `python -m http.server 4173 --bind 127.0.0.1`, then open http://127.0.0.1:4173. Stop the server with Ctrl+C. The page also works when opened directly from disk.

## Editing

- `index.html`: biography, experience, published work, podcasts, speaking highlights, and contact links.
- `styles.css`: colors, typography, responsive layouts, and reduced-motion support.
- `script.js`: mobile menu, Escape dismissal, and focus handling.
- `assets/`: the CV-sourced portrait, podcast thumbnails, and custom favicon.

The page uses DM Sans and Instrument Serif from Google Fonts, with system fallbacks. All other assets are local. Content and navigation remain available without JavaScript.

## Content rules

Career information is based on Rutva's September 19, 2026 CV. Employer documentation is summarized rather than reproduced. Podcast, webinar, conference, recognition, Medium, and LinkedIn destinations come from the CV; podcast titles were verified against YouTube's public metadata. Podcast thumbnails are local copies of the corresponding YouTube thumbnails and link to the original videos.

The IoT Global Network and ARPost articles are shown as publication summaries: their original URLs returned HTTP 404 and a WordPress HTTP 500 error during verification on September 20, 2026, so those links are omitted. The Medium profile remains linked; it is independently indexed under Rutva's name, although direct automated visits are blocked by its security service. LinkedIn also restricts automated visits; its URL matches the supplied CV. Earlier career dates that are ambiguous in the CV are intentionally omitted. Do not add unsupported results, testimonials, or availability claims.

Only Rutva's email and LinkedIn are offered as contact methods. Do not commit the source CV, reference details, phone numbers, or temporary inspection files. There is no CV download, analytics, contact form, or public deployment configuration.

## Verification

Check the page at mobile, tablet, and desktop sizes; keyboard navigation, menu open/close and Escape behavior; anchor links and external links; 200% zoom; reduced motion; and the no-JavaScript fallback. Confirm no horizontal overflow, missing assets, or browser console errors before publishing changes.

Verified in Chromium on September 20, 2026 at 320, 390, 620, 768, 1024, and 1440 CSS pixels, plus 200% text sizing and the effective viewport for 200% zoom. Mobile menu keyboard navigation, Escape focus return, link dismissal, breakpoint reset, reduced motion, and JavaScript-disabled navigation passed. No horizontal overflow, local asset failures, or page script errors were found. Primary text/background contrast pairs exceed 4.5:1. HTML nesting, anchor targets, and the contact-data audit also passed. Screenshots and temporary checks are kept outside the tracked source.
