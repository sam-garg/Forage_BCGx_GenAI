# Task 1: Data Extraction and Analysis

This project focuses on the extraction and analysis of financial data for major technology companies, including Microsoft, Tesla, and Apple. The goal is to evaluate key financial metrics and calculate year-over-year growth to understand performance trends.

## Project Overview

The analysis is performed using a Python Jupyter Notebook (`BCGx.ipynb`). The primary data source is a dataset manually extracted from the SEC's EDGAR database.

**Key features of the analysis include:**
- **Data Extraction**: Extracting the data from EDGAR's
- **Data Loading**: Importing financial data from `final_report.csv`.
- **Data Cleaning**: Handling missing values by imputing them with 0.
- **Financial Analysis**:
    - Calculation of Revenue Growth (%).
    - Calculation of Net Income Growth (%).
    - Analysis of Year-over-Year (YOY) growth for Total Assets, Total Liabilities, and Cash Flow from Operating Activities.
- **Reporting**: Generating summarized reports and analyzed datasets (e.g., `analyzed.csv`, `Summarized_report.csv`).

## Files in the Directory

- **`BCGx.ipynb`**: The main Jupyter Notebook containing the code for data loading, cleaning, and analysis.
- **`final_report.csv`**: The input dataset containing raw financial figures (Revenue, Net Income, Assets, Liabilities, Cash Flow) for the companies.
- **`analyzed.csv`**: The output file containing the original data enriched with calculated growth metrics.
- **`Summarized_report.csv`**: A summary report generated from the analysis.
- **`Final_report.csv`**: Duplicate or related version of the input data.

## Prerequisites

To run this project, you need to have the following installed:

- Python 3.x
- Jupyter Notebook or JupyterLab
- Pandas library

## Setup and Usage

1.  **Clone the repository** or download the project files to your local machine.
2.  **Navigate to the project directory**: `Task 1 - Data Extraction and analysis`.
3.  **Install the required Python packages** (if not already installed):
    ```bash
    pip install pandas notebook
    ```
4.  **Open the Jupyter Notebook**:
    ```bash
    jupyter notebook BCGx.ipynb
    ```
5.  **Run the cells** in the notebook to perform the data extraction and analysis steps.