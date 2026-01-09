# Task 2: FinAI ChatBot

This project implements a simple, rule-based AI chatbot designed to provide financial insights for major technology companies (Microsoft, Tesla, Apple) based on data analyzed in **Task 1**. The chatbot interacts with users via a command-line interface to answer specific queries regarding financial metrics and growth rates.

## Project Overview

The **FinAI ChatBot** acts as a bridge between the user and the processed financial data (`Final_report.csv` and `Summarized_report.csv`). It allows users to quickly retrieve key figures like Total Revenue, Net Income, and Year-over-Year growth rates without manually searching through datasets.

**Key Features:**
- **Interactive CLI**: Simple text-based interface.
- **Company Specific**: specialized support for Microsoft, Tesla, and Apple.
- **Fiscal Year Filtering**: specific data retrieval for years 2022-2025.
- **Rule-Based Logic**: Answers a predefined set of financial questions accurately.

## Data Sources

The chatbot relies on two CSV files generated from the previous data extraction and analysis task:
1.  **`Final_report.csv`**: Contains yearly financial data for each company.
2.  **`Summarized_report.csv`**: Contains aggregated average growth rates over the analyzed period.

## Supported Queries

The chatbot can answer the following questions. Please ensure you type them exactly as shown (or copy-paste) when prompted:

**Metric-Specific Queries (Requires Fiscal Year):**
- What is the total revenue?
- What is the Net Income?
- What is the sum of total assets?
- What is the sum of total liabilities?
- What is cash flow from operating activities?
- What is the revenue growth(%) ?
- What is the net income growth(%) ?
- What is the assets growth(%) ?
- What is the liabilities growth(%) ?
- What is the cash flow from operations growth(%) ?

**Summary Queries (Average Metrics):**
- What is the year by year average revenue growth rate(%)?
- What is the year by year average net income growth rate(%)?
- What is the year by year average assets growth rate(%)?
- What is the year by year average liabilities growth rate(%)?
- What is the year by year average cash flow from operations growth rate(%)?

## Prerequisites

- Python 3.x
- Pandas library

## Setup and Usage

1.  **Navigate to the project directory**: `Task 2 - FinAI ChatBot`.
2.  **Ensure Data Files are Present**: Make sure `Final_report.csv` and `Summarized_report.csv` are in the same directory as the script.
3.  **Run the Chatbot**:
    ```bash
    python FinAI-chatbot.py
    ```
4.  **Interact**:
    - Type **`Hi`** to start the session.
    - Enter the **Company Name** (e.g., Microsoft).
    - Enter the **Fiscal Year** (e.g., 2023).
    - **Enter your query** from the list of supported questions above.
    - Type **`exit`** when asked to start a new session if you wish to quit.

## Files in Directory

- **`FinAI-chatbot.py`**: The main Python script containing the chatbot logic.
- **`Task2.ipynb`**: A Jupyter Notebook used for development and testing of the chatbot logic.
- **`questions.txt`**: A text file listing all valid questions the chatbot understands. 
- **`Final_report.csv`**: Financial dataset (Input).
- **`Summarized_report.csv`**: Summary dataset (Input).
