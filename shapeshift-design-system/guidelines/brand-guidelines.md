# ShapeShift Technologies brand guidelines

ShapeShift Technologies designs and manufactures fibre reinforced facade panels (FRP, GRC/GFRC, GRG). This system matches the live website's consistency layer (v1.4–1.6, September 2026), so documents, slides, drawings and web pages read as one brand. Light only: the brand has no dark theme.

## Content fundamentals

- Write the company name as **ShapeShift Technologies** in text, never "ShapeShift" alone.
- Headings use **sentence case** ("How FRP panels are moulded"). Uppercase is reserved for `label`, `button`, table headers, form labels and footer headings, always letter-spaced 0.08–0.13em.
- Plain, technical, confident. Name the material and the process; no emoji.
- Do not write claims beside the trust badges (certificate numbers, scope, "fully compliant") unless the user supplies the wording.

## Colour

- Body text is `ss-ink` on `ss-white`, `ss-mist` or `ss-paper`. Headings, titles and card titles are `ss-navy`.
- Secondary text (captions, labels, metadata) is `ss-grey`. Never set text in `ss-midgrey` — it is for lines, shapes, icons and diagram fills only.
- `ss-action` green is for buttons and calls to action **only**. Text on it is `ss-action-ink`, with a 1px `ss-action-edge` border; hover is `ss-action-hover`. Never white text on green.
- `ss-cyan` is for rules, bullets, focus outlines, highlights and text 24px or larger. Never put small text on a cyan fill — a coloured band that carries text uses `ss-blue` with `ss-white` text.
- On `ss-navy` bands: headings `ss-white`, body `ss-on-navy-body`, small accents `ss-light-cyan`, focus outline white.
- Neutral dividers are `ss-rule` (navy at 18%). Strong rules are 1–2px solid `ss-navy`.
- Form states: errors use `ss-error-edge` borders and `ss-error-ink` text; warnings use `ss-warning-bg` with a `ss-warning-edge` edge and `ss-warning-ink` text.
- Charts and diagrams take series colours in this order: `ss-navy`, `ss-blue`, `ss-cyan`, `ss-midgrey`, `ss-action`.
- Orange is retired. Never use `#FF9F1C` or the old blue `#0370A6`. The orange and teal inside the GRCA and LRQA badges belong to those badges only.

## Typography

- **Poppins** (`display`, 500 and 600): every heading from `hero` to `h4`, card titles, `label`, `button`, navigation, table headers, form and spec labels.
- **Roboto** (`body`, 400; 500/600 for emphasis): body copy, lists, table cells, form inputs, captions, footer text.
- Load both from Google Fonts: `https://fonts.googleapis.com/css2?family=Poppins:wght@500;600&family=Roboto:wght@400;500;600&display=swap`.
- On the web the scale is fluid; the sizes in the type styles are the desktop maximum and each style's note gives its `clamp()`. `hero`, `h1` and `h2` use `text-wrap: balance`.
- Use tabular numerals (`font-variant-numeric: tabular-nums`) wherever figures line up.
- Documents and slides (A4): H1 26–28pt Poppins 600, H2 18–20pt Poppins 500, H3 14pt Poppins 500, body 10.5–11pt Roboto at 1.45–1.5 line spacing, captions 9pt Roboto in `ss-grey`, labels 8pt Poppins 600 uppercase. Slides scale the same ratios up.

## Spacing and layout

- One scale for every margin, padding and gap: `ss-1` 4px through `ss-8` 64px.
- Sections: hero `ss-8` top and bottom (72px at 1024px wide and below); standard `ss-7` (`ss-5` at 1024px and below); tight `ss-6` (40px at 1024px and below).
- Articles: H2 `ss-6` above, `ss-2` below; H3 `ss-5` above, `ss-3` below; paragraphs `ss-3` below; list items `ss-2` apart. The first heading in a block has no top margin.
- Form field groups `ss-3` apart; labels 7px above the input.
- Corners are `ss-radius` (3px) everywhere; `ss-pill` only for pills and chips. No shadows.
- Touch targets at least `ss-touch` (44px); inputs and mobile menu rows `ss-input` (48px).
- Focus: 2px solid `ss-focus` outline at 2px offset (white on navy).
- Text width: web paragraphs fill their container; documents, slides, drawings and stand-alone pages keep body text to 65–75 characters per line.

## Logo

- Use only the supplied files in **Logos**: `logo-horizontal.png` for headers, title blocks, slide footers and wide layouts; `logo-stacked.png` for covers, title slides and square social tiles.
- Never redraw, trace, regenerate, recolour, stretch, crop, rotate, outline or add effects.
- Place on `ss-white` or `ss-mist` only. The wordmark is near-black: never on `ss-navy`, other dark grounds or busy photos.
- Clear space at least the height of the "TECHNOLOGIES" line. Minimum width: horizontal 120px (30mm), stacked 80px (20mm).

## Trust badges (documents only)

- **Badges** holds `badge-lrqa-iso9001.png` (LRQA ISO 9001) and `badge-grca.png` (GRCA International Full Member).
- Ask the user, once per document, whether to include them and which (both, ISO 9001 only, GRCA only, none). Unattended: leave them out and say so.
- Documents only — reports, proposals, quotes, capability statements, data sheets, letters, certificates. Never on LinkedIn posts, carousels, social tiles, video thumbnails or blog articles.
- Header or footer only, never in the body or the cover hero. 12–15mm tall in A4 (about 45–60px on screen), never taller than the logo beside them.
- Footer (preferred): logo or company details left, badges right, bottom-aligned, `ss-4`–`ss-5` apart, ISO 9001 then GRCA. In multi-page documents use the first page and/or the running footer, not both header and footer.
- Keep a white ground. Do not crop the LRQA teal tile; the GRCA mark needs `ss-white` or `ss-mist` behind it.

## Iconography

- The brand defines no icon set. Draw simple line icons and diagram shapes in `ss-navy`, `ss-blue` or `ss-midgrey`; no emoji.

## Components

- `Button`: the green action button for calls to action, the blue text button for secondary actions.
- `DataTable`: spec and schedule tables.
- `Callout`: notes and warnings.
- `NavyBand`: dark section bands.
- `FormField`: labelled inputs with error state.
- `DocumentFooter`: logo with the trust badges for documents.
