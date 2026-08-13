# My Static Website

A small multi-page static website built with HTML5 and CSS, deployed
with GitHub Pages.

## Pages

| Page | File | What it demonstrates |
|---|---|---|
| Home | `index.html` | Headings, paragraphs, images, bold and italics, a back-to-top anchor link |
| My Hobby | `cycling/index.html` | Semantic HTML5 — `header`, `nav`, `main`, `section`, `footer`, plus `article`, `figure`, `figcaption`, `aside` and `time` |
| Resources | `tables.html` | A table of useful HTML learning resources |
| Shop | `shopping.html` | A responsive Bootstrap 5 product grid with hover effects and a footer contact form |

## Built with

- HTML5
- CSS3 (custom stylesheet in `styles.css`)
- Bootstrap 5 (via CDN, on the shop page only)

## Structure

```
index.html          homepage
styles.css          shared stylesheet
tables.html         resources table
shopping.html       Bootstrap shop layout
cycling/
    index.html      semantic HTML hobby page
```

Every page links to every other through a shared navigation bar.

## Running it locally

No build step and no server needed — open `index.html` in a browser.
