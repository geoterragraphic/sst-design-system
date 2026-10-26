# ShapeShift Technologies design system

Colours, typography, spacing, logos and component styles for ShapeShift Technologies, the fibre reinforced facade panel manufacturer (FRP, GRC/GFRC, GRG). It matches the live website's consistency layer (v1.4–1.6, September 2026), so documents, slides, drawings and web pages read as one brand.

Open `index.html` for the visual brand book. To publish it, enable GitHub Pages for this repository (Settings → Pages → deploy from the main branch, root folder).

## Contents

| Path | What |
| --- | --- |
| `index.html` | Brand book: colours, type, spacing, logos, components, guidelines |
| `guidelines/brand-guidelines.md` | The full usage rules |
| `tokens/tokens.json` | Design tokens as data (colours, type styles, spacing, radius, sizing) |
| `tokens/tokens.css` | The same tokens as CSS custom properties (`--ss-navy`, `--ss-4`, …) |
| `css/fonts.css` | `@font-face` rules for the self-hosted fonts |
| `css/components.css` | Styles for the six components |
| `css/site.css` | Layout for `index.html` only |
| `components/<Name>/` | `example.html` and usage notes for Button, DataTable, Callout, NavyBand, FormField, DocumentFooter |
| `fonts/poppins/`, `fonts/roboto/` | Poppins 500/600 and Roboto 400/500/600, as `.woff2` (web) and `.ttf` (desktop, Office) |
| `assets/logos/` | `logo-horizontal.png`, `logo-stacked.png` |
| `assets/badges/` | `badge-lrqa-iso9001.png`, `badge-grca.png` |

## Using it on a web page

```html
<link rel="stylesheet" href="css/fonts.css">
<link rel="stylesheet" href="tokens/tokens.css">
<link rel="stylesheet" href="css/components.css">

<a class="ss-btn ss-btn--action" href="/contact">Request a quote</a>
```

Load the three files in that order. Then use the tokens in your own CSS, for example `color: var(--ss-navy)` or `padding: var(--ss-5)`.

## Key rules

- Write the company name as **ShapeShift Technologies**, never "ShapeShift" alone.
- Body text `--ss-ink`, headings `--ss-navy`, secondary text `--ss-grey`. Never set text in `--ss-midgrey`.
- Green `--ss-action` is for buttons and calls to action only, with dark text.
- Use the logo files as supplied, on white or `--ss-mist` only. Never redraw or recolour them.
- Trust badges go in document headers and footers only, never on social media or blog posts.

See `guidelines/brand-guidelines.md` for the complete rules.

## Licences

- Poppins and Roboto are licensed under the SIL Open Font License 1.1 (`fonts/*/OFL.txt`). The Roboto static files were instanced from the Google Fonts variable font.
- The ShapeShift Technologies logos are the company's trademarks. The LRQA ISO 9001 and GRCA marks belong to their respective organisations and may be used only as their terms allow. These files are not covered by any open-source licence.
