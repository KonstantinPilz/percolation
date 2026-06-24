# Phase Transitions — interactive percolation

A small interactive essay on how **gradual change builds into a sudden step change**, shown through percolation models. Live at:

**https://konstantinpilz.github.io/percolation/**

Each figure is a real simulation running in the browser (union-find connectivity, no precomputed images).

## Widgets

| # | File | What it shows |
|---|------|---------------|
| 01 | `docs/widgets/square.html` | Site percolation on a square lattice (p_c ≈ 0.593) |
| 02 | `docs/widgets/hex.html` | Hexagonal / triangular-lattice percolation (p_c = ½ exactly) |
| 03 | `docs/widgets/disks.html` | Continuum percolation — overlapping disks (φ_c ≈ 0.68) |
| 04 | `docs/widgets/explosive-curve.html` | Explosive percolation, order-parameter curves (random vs Achlioptas product rule) |
| 05 | `docs/widgets/explosive-graph.html` | The same two rules as the actual networks, side by side |
| 06 | `docs/widgets/mandelbrot.html` | Mandelbrot fractal percolation — the medium itself is a random fractal |
| 07 | `docs/widgets/penrose.html` | Percolation on a Penrose aperiodic tiling (golden-ratio deflation) |

Each widget is a self-contained HTML file with no external dependencies except `docs/theme.css`. The landing page (`docs/index.html`) embeds them via iframes with auto-resize.

## Deploy

GitHub Pages, served from the `main` branch `/docs` folder (legacy build — no Actions needed). To change content, edit files under `docs/` and push to `main`.

## Background

Built as an exploration of the "gradual-then-sudden" / phase-change concept. Pointers: [Recent progress on fractal percolation (2025)](https://arxiv.org/abs/2508.08150) · [Explosive percolation (Science, 2009)](https://www.science.org/doi/10.1126/science.1167782) · [The hat & spectre monotiles (2023)](https://momath.org/the-hat/).
