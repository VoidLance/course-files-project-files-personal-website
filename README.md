# Personal Website

A small, static personal portfolio website created for a software development
course. It presents Alistair Sweeting's background, placeholder project
content, contact details, and a separate image gallery using plain HTML and
CSS.

## Why this project is useful

- Demonstrates a simple multi-page website with no framework or build step.
- Provides responsive layouts for desktop and mobile screens.
- Includes in-page navigation for the portfolio sections and a gallery page.
- Shows examples of CSS styling, embedded content, forms, and basic browser
  JavaScript.
- Is easy to inspect, modify, and use as a starting point for a personal
  portfolio.

## Project structure

| Path | Purpose |
| --- | --- |
| [`Index.html`](Index.html) | Main portfolio page with About, Projects, and Contact sections |
| [`gallery.html`](gallery.html) | Image gallery page |
| [`styles.css`](styles.css) | Main site and gallery styles |
| [`style.css`](style.css) | Shared styles used by the practical activity examples |
| [`Example for Practical Activity/`](Example%20for%20Practical%20Activity/) | Standalone HTML/CSS practice pages, including an embedded map example |

## Getting started

### Prerequisites

No package manager, framework, or build tool is required. You only need a
modern web browser. A local web server is recommended because it handles
relative links consistently.

### Run locally

1. Clone this repository and change into its directory.
2. Start a local static server, for example with Python:

   ```bash
   python3 -m http.server 8000
   ```

3. Open [http://localhost:8000/Index.html](http://localhost:8000/Index.html)
   in your browser.
4. Select **Gallery** from the navigation to open
   [`gallery.html`](gallery.html).

You can also open `Index.html` directly in a browser, although a local server
is preferable for testing navigation and external assets.

### Customize the site

- Update the content in [`Index.html`](Index.html).
- Add or replace gallery items in [`gallery.html`](gallery.html).
- Adjust the visual design in [`styles.css`](styles.css).
- Keep linked files in the same relative locations, or update their links when
  moving them.

The practical activity pages can be opened independently from the
[`Example for Practical Activity/`](Example%20for%20Practical%20Activity/)
directory.

## External resources

The site currently uses a hosted Font Awesome script, Google Fonts, Lorem
Picsum images, and a Google Maps embed. An internet connection is therefore
needed to display those resources. The first gallery images come from
[Lorem Picsum](https://picsum.photos/); the gallery page includes an attribution
note for its image sources.

## Support

For questions or issues:

- Open a [GitHub issue](../../issues).
- Contact the maintainer at
  [alistair.m.sweeting@gmail.com](mailto:alistair.m.sweeting@gmail.com).
- Visit the maintainer's [portfolio](https://alistairsweeting.online).

## Maintainer and contributions

This project is maintained by
[Alistair Sweeting](https://github.com/VoidLance).

Contributions are welcome. Before submitting a pull request:

1. Keep changes focused on the website or its learning examples.
2. Test the affected pages in a modern browser at desktop and mobile widths.
3. Check that relative links and external resources still work.
4. Describe the change clearly in the pull request and include screenshots for
   visual updates where useful.

