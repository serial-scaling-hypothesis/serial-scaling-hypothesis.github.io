# The Serial Scaling Hypothesis — project website

A blog-post-style companion to *The Serial Scaling Hypothesis* by
Liu, Preechakul, Kuwaranancharoen, and Bai ([arXiv:2507.12549](https://arxiv.org/abs/2507.12549)).

**Live site:** https://phizaz.github.io/serial-scaling-hypothesis/

## Structure

```
.
├── index.html              the article
├── styles/                 reset · tokens · main (Fraunces-based)
├── fonts/                  self-hosted Fraunces variable WOFF2
├── scripts/                (reserved; currently empty — sidenote toggles are pure CSS)
└── assets/
    ├── figures/            PNG + SVG figures
    ├── videos/             the three-ball collision loop
    └── serial-scaling-hypothesis-poster.pdf
```

## Local preview

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Credits

- 1-vs-5 balls figure: Jorge Diaz Chao.
- Sudoku denoising figure: adapted from Wewer et al. (2025),
  *Spatial Reasoning with Denoising Models*
  ([arXiv:2502.21075](https://arxiv.org/abs/2502.21075)).
- Li–Yan convergence curve: authors' redraw of the result in Li & Yan (2024),
  *O(d/T) Convergence Theory for Diffusion Probabilistic Models*
  ([arXiv:2409.18959](https://arxiv.org/abs/2409.18959)).
- Body typeface: [Fraunces](https://fonts.google.com/specimen/Fraunces),
  self-hosted, SIL OFL.
