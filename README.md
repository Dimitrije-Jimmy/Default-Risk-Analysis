# Montgomery Ward Challenge: Default Risk Analysis

[![MIT License][MIT-shield]][MIT]

Welcome to the **Montgomery Ward Challenge** repository! This project was given by **NLB d.d.** to analyze and mitigate the rise in default rates among online retail lending clients. The dataset, **`cs-data.csv`**, contains 150,000 client records with 11 key attributes that capture various financial and demographic details. The primary goal was to identify which factors most strongly influence the likelihood of a client defaulting (i.e., `DlqIn2Years`).

## Overview
This analysis explores:
- **Exploratory Data Analysis (EDA)**: Data cleaning, missing value imputation, univariate/bivariate analysis.
- **Feature Engineering**: Handling outliers, transformations, derived features.
- **Statistical & ML Modeling**: Using logistic regression, random forests, and more to evaluate default risk.
- **Reporting with Quarto**: A powerful notebook format supporting code, markdown, and rich output.

**Key Topics Covered**:
- Data preprocessing & transformations
- Correlation and multicollinearity checks
- Visualization of distributions, outliers, correlations
- Model building and evaluation (classification metrics)
- Business insights & final recommendations

## Project Structure
- **`MontgomeryWard_Analysis.qmd`**: The main Quarto notebook containing the EDA, modeling, and results.
- **`MontgomeryWard_Analysis.html`**: The rendered HTML report ("PDF-like" but more interactive) generated from the `.qmd` file.
- **`cs-data.csv`**: The dataset with 150,000 client records and 11 attributes.
- **`README.md`**: You're reading it right now!

## Running the Quarto Notebook
**Quarto** is an open-source scientific and technical publishing system, similar to Jupyter notebooks. To run or compile the `.qmd` file:

1. Install Quarto (see [Quarto Docs](https://quarto.org/docs/) for details).
2. In your terminal, navigate to the project folder.
3. Execute:
   ```bash
   quarto render MontgomeryWard_Analysis.qmd
   ```
   This command will generate an **HTML** version of the notebook in the same folder.

If you prefer not to install Quarto, you can simply open the **`MontgomeryWard_Analysis.html`** file in your web browser to view the interactive report.

## Viewing the HTML Report
- Just double-click `MontgomeryWard_Analysis.html` or open it in your favorite browser. This provides a rich, interactive experience, including foldable code blocks, dynamic tables, and embedded plots.

## Acknowledgment
Special thanks to **NLB d.d.** for providing the dataset and instructions for this challenge.

## License
The contents of this repository are licensed under a [MIT License][MIT].

[![MIT License][MIT-shield]][MIT]

[MIT]: https://opensource.org/license/mit
[MIT-shield]: https://img.shields.io/badge/license-MIT-blue.svg
