# Global Income Inequality Model – SDG 10

## Project Overview
This project provides a data-driven analysis of global income inequality trends, focusing on **Sustainable Development Goal 10 (Reduced Inequalities)**. Using regression modeling, we investigate how socio-economic factors like education spending and unemployment impact the Gini Index in target nations (India, USA, and Brazil).

## Problem Statement
High levels of income inequality hinder economic growth and social cohesion. This project aims to monitor these disparities and provide predictive tools for stakeholders to simulate the impact of policy changes on national inequality profiles.

## Objectives
1.  **Trend Analysis**: Examine Gini Index trends (2014-2023) for target countries.
2.  **Correlation Study**: Analyze the impact of Education Spending and Unemployment on inequality.
3.  **Predictive Modeling**: Implement a Linear Regression model to estimate the Gini Index.
4.  **Scenario Simulation**: Provide an interactive interface for real-time prediction.

## Waterfall Methodology & Team Allocation
The project followed a sequential waterfall model, with each phase documented and credited to specific team members:

### TEAM 1 — PART 1 (Data Preparation)
- **Data Collection**: Adith n k (1ST22AD001)
- **Data Cleaning**: Mohammed IFTEQHAR (1VJ22AI019)
- **Data Preprocessing**: Mohamed Ashas (1VJ22AI017)
- **Feature Engineering**: Abdur Rehman sarim (1VJ22AI001)
- **Data Validation**: Shaik sahil (1VJ22AI029)

### TEAM 2 — PART 2 (Analysis & Implementation)
- **Data Analysis**: Shubha R (1ST22CS200)
- **Technical Analysis Support**: Ritesh (1ME22CS121)
- **Repository Maintenance**: Guruprasad Pujari (2BL23CI402)
- **Results Output Generation**: Sankirana (2BL22CI042)
- **Documentation & Reporting**: Koushalya siddappa Gujjatti (1B022AI012)

## Repository Structure
- `data/raw/`: Original World Bank datasets (Gini, Education, Unemployment).
- `notebooks/`:
    - `01_data_merging.ipynb`: Initial unification logic.
    - `SDG10_FINAL_SUBMISSION.ipynb`: **Definitive project notebook** with modeling, evaluation, and interactive GUI.
- `scripts/`: Python utilities for data processing and header updates.
- `sdg10_gini_model.joblib`: The trained and serialized Linear Regression model.

## Getting Started
1.  **Install Dependencies**:
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn joblib ipywidgets
    ```
2.  **Open the Final Notebook**:
    Navigate to `notebooks/SDG10_FINAL_SUBMISSION.ipynb` to view the full analysis and use the interactive prediction sliders.

---
*Aligned with UN Sustainable Development Goal 10: Reduced Inequalities.*
