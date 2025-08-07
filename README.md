# Daily Household Transactions Analysis

## Project Overview
This project analyzes a dataset of daily household transactions to understand spending and income patterns. The dataset includes transactions with details such as date, amount, category, and income/expense type. The analysis involves data cleaning, exploratory data analysis (EDA), time-series trend analysis, and correlation analysis to uncover insights into transaction behaviors.

## Table of Contents
1. [Project Overview](https://github.com/anmoljaincma/project_4_internship_unified_mentor?tab=readme-ov-file#project-overview)
2. [Data Description](https://github.com/anmoljaincma/project_4_internship_unified_mentor?tab=readme-ov-file#dataset-description)
3. [Prerequisites](#prerequisites)
4. [Analysis Steps](#analysis-steps)
   - [Step 1: Data Cleaning](#step-1-data-cleaning)
   - [Step 2: Exploratory Data Analysis (EDA)](#step-2-exploratory-data-analysis-eda)
   - [Step 3: Time-Series Trend Analysis](#step-3-time-series-trend-analysis)
   - [Step 4: Correlation Analysis](#step-4-correlation-analysis)
5. [Visualizations](#visualizations)
6. [Usage Instructions](#usage-instructions)
7. [Output Files](#output-files)
8. [Future Work](#future-work)

## Dataset Description
The dataset, [raw file](daily_transactions_raw_file.csv), contains 2452 transactions with the following columns:
- `Date`: Transaction date (originally mixed formats: `d/m/y` or `dd/mm/yyyy HH:MM:SS`).
- `Mode`: Payment method (e.g., Cash, UPI).
- `Category`: Transaction category (e.g., Food, Household, Transportation, Salary).
- `Subcategory`: Subcategory of transaction (e.g., Milk, Groceries).
- `Note`: Additional notes (optional).
- `Amount`: Transaction amount (in INR, numerical).
- `Income/Expense`: Type of transaction (Income or Expense).
- `Currency`: Currency (all INR).

The [cleaned dataset](cleaned_daily_transactions.csv) has 2450 rows after removing 2 rows with handling duplicates/missing values and outlier amount value.
