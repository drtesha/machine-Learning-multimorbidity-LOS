 Machine Learning for Heart Failure & Multimorbidity in Older Adults: Systematic Review Code

This repository contains code, data, and supplementary materials for the systematic review:  
Title**: "Machine Learning Models for Predicting lenght of stay  in Older Adults   
Authors: Innocent Tesha


 Repository Structure
- `code/`: Statistical analysis scripts (R/Python/Stata) for:
  - Meta-analysis (if conducted)
  - Risk of bias assessment (PROBAST scoring)
  - Subgroup analysis
  - Performance metric synthesis
- `data/`: Extracted study data and quality assessment files:
  - `study-extraction-data.csv`: Raw data extracted from included studies (PICOS, performance metrics, bias scores)
  - `probast-scores.xlsx`: PROBAST risk of bias assessments for each included study
- `supplementary-materials/`:
  - PRISMA flow diagram raw data
  - Additional subgroup analysis tables
  - Model comparison matrices

## How to Use This Repository
1. Clone or download the repository (see "Accessing the Files" below).
2. Install required software/packages (e.g., R: `tidyverse`, `metafor`; Python: `pandas`, `scikit-learn`).
3. Run scripts in the `code/` folder in sequential order (e.g., `1_data-cleaning.R` → `2_meta-analysis.R`).
4. Refer to `data/` files for raw inputs and `supplementary-materials/` for additional outputs.

 Software Requirements
- R Version 4.3.0+ 
- Required packages: [List all packages, e.g., `metafor`, `ggplot2`, `dplyr`, `caret`]
- For reproducibility, use `renv` (R) or `conda` (Python) to freeze package versions (see `renv.lock` or `environment.yml` in `code/`).

 Accessing the Files
- Clone the repo (for advanced users): `git clone https://github.com/[your-username]/[your-repo-name].git`
- Download ZIP: Click the green "Code" button → Select "Download ZIP" (for beginners).

 License
This work is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.  
*Note: Choose a license that aligns with journal requirements—MIT is standard for open science.*

## Contact
For questions about the code or data, contact: Innocent Tesha ([drinnocenttesha@gmail.com])
