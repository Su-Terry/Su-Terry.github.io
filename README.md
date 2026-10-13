# su-terry.github.io

Personal homepage of Chih-Hai (Terry) Su, served by GitHub Pages at https://su-terry.github.io.

The site is a single static page: everything lives in `index.html`. There is no build step (`.nojekyll` turns Jekyll off).

## Updating

- **News**: add a new `<li>` at the top of `#newsList`. Items with `class="old"` stay collapsed behind "Show older news"; keep the latest three without it.
- **Publications**: copy an `<article class="pub">` block. Add `first` to its class to highlight a first-author paper, and wrap your own name in `<span class="me">`.
- **Teaser images**: `assets/img/`, ideally JPG about 1200px wide.
- **BibTeX**: `assets/bib/`.
- **CV**: replace `assets/files/CV_Chih-Hai_Su.pdf` (keep the file name so the links keep working).
- **Footer date**: update "Last updated" at the bottom of `index.html`.

## Analytics

Visits are counted with [GoatCounter](https://su-terry.goatcounter.com) (no cookies). Links with a `data-goatcounter-click="name"` attribute are also counted as click events, e.g. `cv`, `scholar`, `spf-arxiv`. Give new links the same attribute to track them.
