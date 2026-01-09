# BCGx Financial Analysis & AI ChatBot Project

Welcome to the BCGx Data Science and AI Engineering Virtual Experience project. This repository contains the solution for the Financial Data Extraction and Analysis project, split into two main tasks. The project focuses on analyzing financial data for major tech companies (Microsoft, Tesla, Apple) and interacting with that data using a rule-based AI chatbot.

## Project Structure

The project is organized into two main directories, each corresponding to a specific task:

### [Task 1: Data Extraction and Analysis](./Task%201%20-%20Data%20Extraction%20and%20analysis)
This task focuses on the foundational work of processing financial data.
-   **Goal**: Extract, clean, and analyze financial data from the SEC EDGAR database.
-   **Key Activities**:
    -   Loading raw financial data.
    -   Data cleaning and imputation of missing values.
    -   Calculating Year-Over-Year (YoY) growth rates for Revenue, Net Income, Assets, Liabilities, and Cash Flow.
    -   Generating summary reports for further usage.
-   **Main File**: `Task1.ipynb and Task2.ipynb`

### [Task 2: FinAI ChatBot](./Task%202%20-%20FinAI%20ChatBot)
This task builds upon the analyzed data to create an interactive tool.
-   **Goal**: Develop a rule-based AI chatbot to answer financial queries.
-   **Key Activities**:
    -   Using the `Final_report.csv` and `Summarized_report.csv` generated in Task 1.
    -   Implementing a command-line interface (CLI) for user interaction.
    -   Providing specific answers to queries about Revenue, Net Income, and Growth metrics for specific fiscal years.
-   **Main File**: `FinAI-chatbot.py`

## Getting Started

To explore this project:

1.  **Clone the repository**.
2.  **Start with Task 1**: Navigate to the `Task 1 - Data Extraction and analysis` folder to review the data analysis process in the Jupyter Notebook.
3.  **Proceed to Task 2**: Navigate to the `Task 2 - FinAI ChatBot` folder to run the chatbot and interact with the processed data.

For detailed instructions on how to run each part, please refer to the `README.md` files located within each task's directory.

## Technologies Used
-   **Python**: Core programming language.
-   **Pandas**: For data manipulation and analysis.
-   **Jupyter Notebook**: For interactive coding and documentation.

---
*This project is part of a virtual experience program simulating real-world financial data science tasks.*
