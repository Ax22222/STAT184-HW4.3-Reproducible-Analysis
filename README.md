# STAT184-HW4.3-Reproducible-Analysis

## Overview
This repository contains the reproducible data analysis workflow, Quarto source code, rendered PDF report, and supporting data/image assets for **STAT 184 Homework #4.3**.

## Repository Contents
* `README.md` – Project overview, file directory, and reproduction instructions.
* `PLAN.md` – GitHub workflow and analytical project plan.
* `HW4_3.qmd` – Self-contained Quarto source document containing all R code, narrative interpretations, and appendices.
* `HW4_3.pdf` – Final compiled PDF report rendered from `HW4_3.qmd`.
* `teams.csv` – NCAA Women's Basketball team metadata used in Section B.
* `calcium.csv` – Longitudinal serum calcium dataset used in Section D.
* `CopilotPlot.png` & `copilot_pain_plot.png` – Generative AI comparison figures embedded in Section D.

## How to Reproduce
1. Clone this repository:
   ```bash
   git clone https://github.com
   ```
2. Open `HW4_3.qmd` in RStudio or Posit Cloud with `tidyverse`, `knitr`, and `patchwork` installed.
3. **Data Note:** NCAA Women's Basketball box score data (`team_box.csv`) exceeds GitHub's 25 MB file limit and can be downloaded locally using `wehoop::load_wbb_team_box()` before rendering.
4. Click **Render** in RStudio/Posit Cloud to regenerate `HW4_3.pdf`.

## Author
## Project Plan
See [`PLAN.md`](PLAN.md) for the complete GitHub workflow and analytical steps, which are now finalized and merged.

## Author & Contact
* **Sparsh Srivastava** – Penn State University (STAT 184)
* **Email:** svs7538@psu.edu

