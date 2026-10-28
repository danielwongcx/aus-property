# AU residential PM mini-SaaS — first-cut study

A one-page study Daniel can send to the person building [VIC Property Hub](https://vicpropertyhuberp.vercel.app/). It reads that browser demo against [PropertyME](https://www.propertyme.com/) and sketches what the servers might cost if the wedge became a product.

The Hub link is a **browser demo** (`localStorage` key `vph41`). It is not a production SaaS. This repository is the study, not the product.

**Researched 28 October 2026.** Prices are USD list estimates unless marked AUD. Vendors change them. The page is not legal, financial, or trust-accounting advice.

## Read the page

- On GitHub Pages, once enabled: [https://danielwongcx.github.io/aus-property/](https://danielwongcx.github.io/aus-property/)
- On your machine: open `index.html`, or from this folder run `python3 -m http.server` and visit `http://127.0.0.1:8000`

## Turn on GitHub Pages

In the repo: **Settings → Pages → Build and deployment → Deploy from a branch**. Choose branch `main` and folder **`/ (root)`**. Save.

There is no build step and no GitHub Action. `.nojekyll` is included so Pages serves `index.html` as a static file.

## What is on the page

- Thesis: do not clone PropertyME; trust is the buy; the wedge is VIC-first, small rolls, or one sharp workflow
- Pain → function map
- What the Hub demo actually contains, and the gaps
- A compact Hub vs PropertyME comparison
- Diagrams: nested wedge, build phases, monthly cost bands
- Phases A / B / C with the suggested stack, build-time ranges, and source links

Figures come from the 28 October 2026 study and the vendor pages linked in the footnotes. They are not a quote.
