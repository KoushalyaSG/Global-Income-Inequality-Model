# Global Income Inequality Model – SDG 10

## Project Objective
This project aims to analyze and model global income inequality trends, aligning with **Sustainable Development Goal 10 (Reduced Inequalities)**. The goal is to identify patterns, drivers, and potential interventions to reduce inequality within and among countries.

## SDG 10 Alignment
This project directly supports SDG 10 by providing data-driven insights into income distribution and economic disparities. By modeling these factors, we contribute to the global effort to ensure no one is left behind.

## Data Source
The primary data source for this project is the **World Bank**. We utilize their comprehensive datasets on income, GDP, and social indicators to build our models.

## Repository Structure
- `data/raw/`: Contains original, unmodified datasets. **Important: Raw data must not be modified.**
- `data/processed/`: Contains cleaned, merged, and preprocessed data ready for analysis.
- `notebooks/`: Jupyter notebooks detailing the data pipeline and modeling process.
- `reports/`: Final reports and summaries of findings.
- `meeting_logs/`: Documentation of project meetings and decisions.
- `meeting_screenshots/`: Visual records of project discussions and progress.
- `requirements.txt`: Python dependencies required for the project.

## Running the Data Merging Script
If you prefer not to use Jupyter Notebooks, you can run the data merging logic directly from your terminal:

1.  **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```
2.  **Run the script**:
    ```bash
    python scripts/data_merging.py
    ```
    This will process the raw Excel files and save the output to `data/processed/merged_dataset_v1.csv`.

## Notebook Usage
Alternatively, you can use the Jupyter Notebook:
1.  Open `notebooks/01_data_merging.ipynb` in Anaconda or VS Code.
2.  Ensure your kernel is set to an environment with `pandas` and `xlrd` installed.

---
*Developed for academic purposes to monitor and model global income inequality.*
