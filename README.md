# Life Expectancy Analysis

Welcome to the **Life Expectancy Analysis** repository. This project provides a comprehensive framework for analyzing life expectancy data using World Bank indicators. It includes an R package, sample analysis files, and an interactive dashboard for exploring relationships between socioeconomic factors and life expectancy.

## Contents

### Data
The `data/` directory contains datasets used for our analyses. These datasets were processed to ensure consistency and reliability for modeling and visualization.

### Image
The `image/` directory includes visual assets related to the project, such as figures or plots generated during exploratory data analysis.

### Sample Analysis
We provide a sample analysis workflow to demonstrate how to use the tools developed in this project:
- **`final_sample_analysis.Rmd`**: An R Markdown file showcasing the complete analysis pipeline, from data preprocessing to predictive modeling.
- **`final_sample_analysis.html`**: The rendered HTML file from the R Markdown analysis.

### Dashboard
The interactive dashboard and its source file are provided for deeper exploration:
- **`dashboard.Rmd`**: The R Markdown file used to create the interactive Shiny dashboard.
- [Life Expectancy Dashboard](https://ihpte0-wenqing-zhang.shinyapps.io/proj4/): Access the live dashboard.

The dashboard allows users to:
- Select target years and predictors.
- Customize train-test splits and modeling parameters.
- Compare results across multiple machine learning models, including linear regression, random forest, support vector machines, and gradient boosting.

### Package
The **WorldbankAnalysis** R package is the backbone of this project. It enables users to fetch, preprocess, and analyze World Bank data seamlessly:
[WorldbankAnalysis GitHub Repository](https://github.com/ggui6809/WorldbankAnalysis)

## How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/<your-group-repo>.git
   ```
2. Install the **WorldbankAnalysis** R package:
   ```R
   # Install directly from GitHub
   devtools::install_github("ggui6809/WorldbankAnalysis")
   ```
3. Open the `final_sample_analysis.Rmd` or `dashboard.Rmd` file in RStudio to explore the analysis pipeline and dashboard development.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.