# Project Workflow & Analytical Plan

## 1. GitHub Workflow Plan
* **Issue Tracking:** Track major deliverables using labeled GitHub Issues (`#1` for documentation/planning, `#2` for Quarto analysis and rendered assets).
* **Branching Strategy:** Create separate feature branches (`docs-setup` and `add-analysis`) rather than committing directly to `main`.
* **Pull Requests & Linking:** Open Pull Requests for each feature branch and include `Closes #1` or `Closes #2` in the PR description to automatically close issues upon merging.

## 2. HW #4.3 Analytical Plan
* **Data Import & Cleaning:** Load raw dataset(s) into R, inspect variable types, and handle missing or malformed values using `dplyr` and `tidyr`.
* **Exploratory Analysis & Visualization:** Generate summary statistics and clean, well-labeled plots using `ggplot2` to answer the assignment prompts.
* **Reproducible Reporting:** Combine narrative explanations, clean R code chunks, and outputs inside a single self-contained `.qmd` file and render to PDF.
