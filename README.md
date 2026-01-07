## STATS 720 — Data Science Portfolio

This repository contains a set of Quarto notebooks (.qmd) demonstrating statistical modeling and simulation work in R. It is set up to run reproducibly in RStudio and to render a small portfolio website suitable for GitHub Pages.

These projects were completed during a graduate course in statistical modelling at McMaster University taught by Prof. Ben Bolker, a leading figure in computational statistics. The work spans advanced linear and generalized modelling frameworks, including GLM, MLM, GLMM, and GAM.

### Requirements
- R (≥ 4.1) and RStudio (latest)
- Quarto (install from `https://quarto.org` or via RStudio if prompted)

### Quickstart (RStudio)
1. Open the RStudio project file: `stats720-portfolio.Rproj`.
2. Render a single notebook: open a `.qmd` and click “Render”, or run:
   ```r
   quarto::quarto_render("Project_1.qmd")
   ```
3. Render the entire website to `docs/` (for GitHub Pages):
   ```r
   quarto::quarto_render()
   ```

### Project structure
- `Project_*.qmd` — Quarto notebooks (analysis and writeups)
- `Project_*.pdf` / `Project_4.html` — rendered outputs (legacy)
- `olymp1.csv` — input data used in Project 1
- `_quarto.yml` — site configuration (navbar, theme, output to `docs/`)
- `docs/` — site output directory (committed for GitHub Pages)
- `stats720-portfolio.Rproj` — RStudio project file

### Data
`olymp1.csv` must remain in the project root for the notebooks to run. 

### License
MIT — see `LICENSE`.



