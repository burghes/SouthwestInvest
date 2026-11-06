# Invest South West – website

One-page inward investment site for **Invest South West**, a partnership of councils in Cornwall, Devon, Plymouth, Torbay, BCP, Dorset, Somerset and Wiltshire. Hosted on GitHub Pages at https://southwestinvest.co.uk/

## How this repo works
- Single self-contained `index.html` (CSS and SVG inline; Google Fonts: Oswald and Inter). No build step.
- Pushing to the default branch publishes the site. Always show me the diff and ask before committing or pushing.
- Keep the `CNAME` file (if present) unchanged.

## Brand rules
- Name is **Invest South West** (never "Invest in the South West", never "True South West").
- Strapline: "Room to grow. Ready to go."
- Logo: compass mark + "INVEST / SOUTH WEST" on two lines, all words Oswald Bold, same size. Use the outlined artwork in `brand/ISW_Logo_Pack_v2/svg/` – never re-typeset it. On the site it is an inline `<symbol id="logo-rev">`.
- Colours: Deep Sea #0E3B5C, Gold #F2B33D, Teal #0F7478, Slate #4A5A66, Mist #E8F0F3, White. All text/background pairs must meet WCAG 2.2 AA.
- Geography: always exactly Cornwall, Devon, Plymouth, Torbay, BCP, Dorset, Somerset and Wiltshire. Don't add other areas.
- Partner council logos are in `assets/partners/` and appear in the footer, in the same order as the geography list.
- UK English, plain English. Public sector: politically neutral, no unverified claims ("best place in the UK" etc.). Every statistic or claim needs a source in the footer Sources list.

## Pending
- Imagery is being reworked after partner feedback (too abstract). Real place photography to replace illustrations once partners supply images and licences – check licences before adding any photo.
- Domain may move to investsw.co.uk later: then update canonical, og:url, JSON-LD url and mailto links together.
- Trademark/name checks on "Invest South West" are not yet complete.
