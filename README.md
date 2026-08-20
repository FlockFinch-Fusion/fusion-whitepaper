# Fusion Whitepaper

This repository contains the English research-positioning paper for Fusion.
The paper is written in LaTeX and is intentionally vision-led, evidence-backed,
and literature-aware rather than structured as a product manual.

## Build

```bash
make
```

The generated PDF is written to `build/main.pdf`.

## Source layout

- `main.tex` owns document metadata and section order.
- `sections/` contains the paper body.
- `references.bib` contains cited research.
- `literature-review/` is a local research input and is intentionally ignored by Git.

Orange `Evidence pending` markers identify claims that require a final,
provenance-complete benchmark result before public release.

