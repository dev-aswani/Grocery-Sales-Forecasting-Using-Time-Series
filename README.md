# Time Series Analysis Project

This repository contains all the necessary resources for a multivariate time series analysis project. The project involves analyzing sales data, applying statistical models, and interpreting results. Below, you'll find a breakdown of the project structure, purpose, and usage instructions.

---

## Project Overview

The primary goal of this project is to perform exploratory data analysis, build time series models, and generate predictions for sales data in Favorita grocery stores across Ecuador. It involves analyzing sales for five categories of products POULTRY, MEATS, LIQUOR, PREPARED FOODS, FROZEN FOODS and project sales 15 days into the future. The project includes datasets, scripts for analysis, outputs, and a detailed report documenting the approach and findings.

---

## Repository Structure

### 1. `code/`

This folder contains the R scripts used for data exploration and modeling.

-   `eda+var.R`: Performs exploratory data analysis and applies vector autoregression (VAR) models to the datasets.

### 2. `data/`

Contains the datasets used for time series analysis.

-   **`sample1_sales_timeseries.csv`**: Sales data for sample 1.
-   **`sample2_sales_timeseries.csv`**: Sales data for sample 2.
-   **`sample3_sales_timeseries.csv`**: Sales data for sample 3.
-   **`sample4_sales_timeseries.csv`**: Sales data for sample 4.
-   **`sample5_sales_timeseries.csv`**: Sales data for sample 5.

### 3. `output/`

Contains the output generated by the scripts.

-   **`PredictedValuesVAR.csv`**: The predicted sales values generated by the VAR model.

### 4. `Report/`

Contains the final report summarizing the analysis and findings.

-   **`Report.docx`**: A comprehensive report detailing the approach, methodology, results, and interpretations.

---

## How to Use

1. **Prerequisites:**

    - Install R and ensure necessary packages (e.g., `forecast`, `tsibble`, `vars`) are installed.
    - Familiarity with time series concepts like VAR modeling.

2. **Steps:**

    - Place the datasets in the `data/` folder.
    - Run the script `eda+var.R` from the `code/` directory for analysis.
    - View the predictions saved in `output/PredictedValuesVAR.csv`.

3. **Report & Problem Statement:**
    - Refer to the `Report/` folder for detailed insights.
    - Use the problem statement in `Problem Statement/` to understand project objectives.

---

## Key Highlights

-   **Time Series Models:** The project applies advanced multivariate time series models like VAR to multi-sample sales data.
-   **Automated Predictions:** Scripts generate predictions that can be used for decision-making.
-   **Documentation:** A comprehensive report and problem statement guide you through the analysis.

---

## Contact

For any questions or feedback, feel free to reach out via the repository's issue tracker or directly email the project contributors.

---
