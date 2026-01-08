## Advanced Statistical Modelling (STATS 720) — Portfolio

Interactive analyses and write-ups for STATS 720 (Statistical Modelling), authored in Quarto and rendered as a website.

- Live site: `https://KostasBanos.github.io/Advanced_Linear_Models/`
- Example page: `https://KostasBanos.github.io/Advanced_Linear_Models/Project_4.html`

The website provides interactive HTML outputs (e.g., Plotly figures with zoom/hover) so you can explore results without running code locally. PDF renders are also included for archival and offline reading.

------------------------------------------------------------------------

## Overview

This repository contains Quarto notebooks (`.qmd`) developed for STATS 720 at McMaster University (instructor: Prof. Ben Bolker). The work emphasizes:

- rigorous statistical reasoning and communication
- modern modelling workflows in R with reproducibility
- principled model comparison and diagnostics

Topics include GLMs, LMMs/MLMs, GLMMs, bias-reduced/penalized/Bayesian estimation, simulation-based inference and bootstrap methods, residual diagnostics, spline-based nonlinear effects, and likelihood/resampling-based comparisons.

------------------------------------------------------------------------

## Requirements

- R (≥ 4.1) and RStudio (current recommended)
- Quarto (install from `https://quarto.org` or via RStudio)

You may need to install the R packages used in each project. Open a `.qmd` file to see the libraries loaded at the top and install any that are missing.

##  Methodological Scope

Across the projects, the following modeling frameworks and techniques are explored:

-   **Generalized Linear Models (GLM)**
-   **Linear and Multilevel Mixed Models (LMM / MLM)**
-   **Generalized Linear Mixed Models (GLMM)**
-   **Bias-reduced, penalized, and Bayesian estimation**
-   **Simulation-based inference and bootstrap methods**
-   **Model diagnostics and residual analysis**
-   **Nonlinear effects and spline-based modeling**
-   **Likelihood-based and resampling-based model comparison**

------------------------------------------------------------------------

## Quick start

### Option A: RStudio
1. Open the RStudio project: `stats720-portfolio.Rproj`.
2. Render a single notebook (open a `.qmd` and click “Render”) or run:

```r
quarto::quarto_render("Project_1.qmd")
```

3. Render the entire site to `docs/` (for GitHub Pages):

```r
quarto::quarto_render()
```

### Option B: Terminal (Quarto CLI)
From the project root:

```bash
quarto render            # build all pages into docs/
quarto render Project_1.qmd
quarto preview           # local dev server with live reload
```

------------------------------------------------------------------------

## Project structure

- `index.qmd` — site landing page
- `Project_*.qmd` — notebooks for Projects 1–5
- `docs/` — site output (committed for GitHub Pages)
- `_quarto.yml` — site config (navbar, theme, output dir)
- `data/olymp1.csv` — input data used in Project 1
- `Project_Files/` and `docs/*_files/` — figures/assets generated during rendering
- `stats720-portfolio.Rproj` — RStudio project file
- `LICENSE`, `CITATION.cff`, `README.md`

------------------------------------------------------------------------

## Publishing (GitHub Pages)

This site is configured to render into `docs/`. To publish:
1. Build the site (RStudio “Render” or `quarto render`).
2. In your GitHub repository settings, set Pages → “Deploy from a branch” and select the `main` (or default) branch with `/docs` as the folder.
3. Visit the GitHub Pages URL after it deploys.

------------------------------------------------------------------------

## Citation

If you use or reference this work, please cite it. See `CITATION.cff` for full metadata.

Example (APA-like):

> Banos, K. (2026). STATS 720 — Data Science Portfolio (v1.0.0) [Software]. MIT License. `https://github.com/KostasBanos/Advanced_Linear_Models`

------------------------------------------------------------------------

## Acknowledgements

Course: STATS 720 — Statistical Modelling, McMaster University.  
Instructor: Prof. Ben Bolker.

------------------------------------------------------------------------

## License

MIT — see `LICENSE`.
