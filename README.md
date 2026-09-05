# Harvard College Fund, website redesign

A redesign mockup of the Harvard College Fund site
(`alumni.harvard.edu/college/college-giving/hcf`), built for the HCF Marshal
application. Four static pages, no build step and no dependencies: open
`index.html` in a browser, or serve the folder over any static server.

## Pages

| File | Page |
| --- | --- |
| `index.html` | Harvard College Fund landing page |
| `hcf-staff-directory.html` | HCF Staff Directory |
| `hcf-giving-recognition.html` | Giving and Recognition |
| `hcf-associates.html` | Associates |

## Notes

- Every image is embedded as a base64 data URI, so the pages render offline.
  This is why `index.html` is around 1.1 MB.
- Type is Libre Baskerville and Open Sans, loaded from Google Fonts. Without a
  network connection the pages fall back to Georgia and Helvetica.
- The landing page holds three interactive pieces: an autoplaying timeline
  carousel with a pause control and per-year popups, a rotating quote
  carousel, and a horizontally scrolling events rail.
- Layout is built on one content column, 1120px wide, so every heading, card
  grid, and rail shares a single left edge.
- Content and figures were taken from the live HCF page and from
  `harvard2026.com/hcf`. The staff directory lists real Harvard staff, which
  is why this repository is private.
