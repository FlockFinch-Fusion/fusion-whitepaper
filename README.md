# Fusion Whitepaper

This repository contains Fumo Lab's English whitepaper for Fusion. It is
written in LaTeX and is intentionally vision-led and evidence-backed: the
document presents Fusion's motivation, design philosophy, innovation, and
long-term potential rather than following the structure of a technical research
paper or product manual.

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
