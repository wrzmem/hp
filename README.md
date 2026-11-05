# Borussia Wien

Dependency-free static website reflecting the content of http://www.borussia-wien.at/ retrieved on 5 November 2026.

Open `index.html` directly, or serve this directory with `python3 -m http.server 8000`. Deploy the repository root to any static web host, including GitHub Pages; no build step, package installation, or server-side code is required.

Edit the content and event programme in `index.html` and the responsive presentation in `styles.css`. Content is a snapshot, not automatically synchronized with the original website.

The original photo links, MKV video, map, Facebook page, and imprint remain external links. The original image assets timed out during retrieval, so the page uses a text wordmark and CSS artwork instead of depending on unavailable images. No external fonts, scripts, embeds, or trackers load automatically. The broken WordPress contact form is replaced by an email link; sending messages requires an email application.

The source programme lists 28 September 2026 as a Friday, although it is a Monday. The date is retained without the inconsistent weekday. Confirm programme details with the club.

There is no existing automated test, lint, or build infrastructure. Validate changes by serving the files and checking navigation, all twelve events, external links, and desktop/mobile layout in a browser.