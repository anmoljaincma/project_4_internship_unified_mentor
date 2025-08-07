# Daily Household Transactions Analysis

## Table of Contents
1. [Project Overview](https://github.com/anmoljaincma/project_4_internship_unified_mentor/blob/main/README.md#1-project-overview)
2. [Data Description](https://github.com/anmoljaincma/project_4_internship_unified_mentor/blob/main/README.md#2-dataset-description)
   ### [Python file link of next steps](Project_4_Unified_Mentor_Internship.ipynb)
4. [Import Libraries and Load Data](https://colab.research.google.com/drive/1DcmIP1nISBQf2N06cFzsitNqe9up9rJE#scrollTo=G0g5L4VrV54q)
5. [Data Cleaning](https://colab.research.google.com/drive/1DcmIP1nISBQf2N06cFzsitNqe9up9rJE#scrollTo=NXkOUivra6sn)
6. [Exploratory Data Analysis (EDA)](https://colab.research.google.com/drive/1DcmIP1nISBQf2N06cFzsitNqe9up9rJE#scrollTo=Wp7wimAtvwP3)
7. [Time Series Analysis](https://colab.research.google.com/drive/1DcmIP1nISBQf2N06cFzsitNqe9up9rJE#scrollTo=L1cqqOZ3akL8)
8. [Correlation Analysis](https://colab.research.google.com/drive/1DcmIP1nISBQf2N06cFzsitNqe9up9rJE#scrollTo=z2FauTAnzVgI)
9. [Generate Report](https://colab.research.google.com/drive/1DcmIP1nISBQf2N06cFzsitNqe9up9rJE#scrollTo=b575fccc)

## 1. Project Overview
This project analyzes a dataset of daily household transactions to understand spending and income patterns. The dataset includes transactions with details such as date, amount, category, and income/expense type. The analysis involves data cleaning, exploratory data analysis (EDA), time-series trend analysis, and correlation analysis to uncover insights into transaction behaviors.

## 2. Dataset Description
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
