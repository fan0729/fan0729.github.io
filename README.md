# Fan Zhang · Portfolio

My personal site: **[fan0729.github.io](https://fan0729.github.io)**

UCLA Anderson MSBA ’27. I turn messy data into decisions people actually use, and I’m always exploring what AI makes possible.

## What’s on the site

- **Cover:** a sewn-in clothing label with name, roles and “Made in Qingdao”, plus quick links
- **Editor’s letter:** four things about me
- **Projects:** A/B testing framework, Landfall (team hackathon app), a material handbook tool, and Fan’s Personal Matters
- **Experience & education:** WTL Design, Los Angeles Apparel, USC research, UCLA Anderson and USC
- **Résumé:** one-click PDF download
- **Contact:** email, [LinkedIn](https://www.linkedin.com/in/fan-zhang-analyst/) and [GitHub](https://github.com/fan0729)

## How it’s built

A single static page styled like a magazine issue, with no build step: `index.html` with inline CSS, served by GitHub Pages from the `main` branch.

| Path | What it is |
|---|---|
| `index.html` | The whole site |
| `img/` | Project images, organization logos and the link-preview image (`og.jpg`) |
| `lace-trim.svg` | The lace edge on the cover label |
| `pinyon-1.svg` | The script “Fan Zhang” wordmark |
| `Fan_Zhang_Resume.pdf` | The résumé the download buttons serve |
| `favicon.svg`, `favicon.png`, `apple-touch-icon.png` | The FZ logo |

Fonts: Bodoni Moda, EB Garamond and DM Sans from Google Fonts; the wordmark is Pinyon Script, saved as SVG paths.

## Updating

- **New résumé:** replace `Fan_Zhang_Resume.pdf` with the new file under the same name.
- **Text or projects:** edit `index.html`.
- Push to `main`, and the live site updates in a minute or two.
