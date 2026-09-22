# Alejandra Fajardo Beltrán — Personal Site

One-page bilingual (ES/EN) resume site.

- `index.html` — the site. Language copy lives in the `COPY` object in the inline script at the bottom.
- `support.js` — small render runtime the page depends on.
- `AlejandraFajardoBeltran-Resume-EN.pdf` / `-ES.pdf` — printable resumes linked from the "Printable resume" / "Hoja de vida" buttons.

Served by GitHub Pages from `main`.

## Web resume pages

`resume-en.html` and `resume-es.html` are the styled resume pages, served at
`/resume-en.html` and `/resume-es.html`. They depend on `support.js`,
`doc-page.js` and `image-slot.js`.

The printable PDFs are the separate `AlejandraFajardoBeltran-Resume-*.pdf` files
linked from the site's resume buttons.
