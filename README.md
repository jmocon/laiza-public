# Laiza — public pages

The user guide and privacy policy for **Laiza**, an offline-first ebook and fanfiction
reader for Android.

Served by GitHub Pages:

| Page | URL |
|---|---|
| Introduction | <https://jmocon.github.io/laiza-public/> |
| Guide | <https://jmocon.github.io/laiza-public/guide.html> |
| Privacy policy | <https://jmocon.github.io/laiza-public/privacy.html> |

All three are plain static HTML with one shared stylesheet — no build step, no Jekyll, no
external requests — **including no web font**, since a site that says nothing leaves
your device should not fetch a typeface from a third party on load. `.nojekyll` tells
Pages to serve the files as they are.

The app's source lives in a separate private repository.
