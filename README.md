# Equity Fund Performance Analysis

### Description
This repository contains a Python program developed to analyze the performance of a U.S. equity fund comprising 150 companies across multiple industries. The analysis is based on the most recent quarterly data and focuses on metrics like debt-to-equity ratio, debt-to-income ratio, and state-wise performance statistics. The program loads data from an Excel file, performs various data processing tasks, and generates insights to help the fund managers rebalance their holdings.

### Features
- **Data Import**: Reads the dataset from an Excel file.
- **Duplicate Identification**: Detects and removes duplicate records.
- **State-wise Grouping**: Groups data by company location (state) and calculates descriptive statistics (mean, median, min, max) for key financial metrics.
- **Debt-to-Equity Filtering**: Filters businesses with negative debt-to-equity ratios.
- **Debt-to-Income Ratio Calculation**: Calculates the debt-to-income ratio for each company.
- **Data Export**: Outputs the results into new Excel files for further analysis.

### Files
- `D598 Data Set.xlsx`: The dataset containing the financial data for 150 U.S. companies.
- `analysis_script.ipynb`: The Jupyter Notebook containing the Python code for data analysis.
- `grouped_statistics.xlsx`: The output file containing descriptive statistics for each state.
- `negative_debt_equity.xlsx`: The output file containing companies with negative debt-to-equity ratios.
- `updated_with_debt_to_income.xlsx`: The final data file, including the calculated debt-to-income ratios.

### How to Use
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/D598-Equity-Fund-Analysis.git
    ```
2. Open the Jupyter Notebook `analysis_script.ipynb`.
3. Run the notebook to perform the data analysis.

### Requirements
- Python 3.x
- pandas
- numpy
- Jupyter Notebook
- openpyxl (for handling Excel files)

Install the dependencies using:
```bash
pip install pandas numpy openpyxl
```
