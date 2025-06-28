# San Francisco Salaries Data Analysis

This project performs a detailed analysis of public employee salaries in San Francisco using the [SF Salaries Dataset](https://www.kaggle.com/kaggle/sf-salaries). It explores salary distributions, missing data, job titles, compensation patterns, and year-over-year trends using Python and Pandas.

## Project Overview

This project covers:

- Loading and inspecting the dataset
- Cleaning missing values and dropping irrelevant columns
- Exploratory data analysis on:
  - Salary distributions (`BasePay`, `TotalPay`, etc.)
  - Missing values (matrix + counts)
  - Compensation by job title
  - Highest and lowest paid employees
  - Trends by year
  - Job title frequency
- Identifying outliers and anomalous entries
- Data visualization with `matplotlib`, `seaborn`, and `missingno`

## Dataset

Sourced from Kaggle: [SF Salaries Dataset](https://www.kaggle.com/kaggle/sf-salaries)  
It includes salary records for San Francisco public employees from 2011–2014.

Key columns:
- `BasePay`, `OvertimePay`, `OtherPay`, `Benefits`
- `TotalPay`, `TotalPayBenefits`
- `JobTitle`, `EmployeeName`, `Year`

## Tech Stack

- Python 3.10+  
- Pandas  
- NumPy  
- Seaborn  
- Matplotlib  
- Missingno  
- Jupyter Notebook  

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/sf-salaries-analysis.git
   cd sf-salaries-analysis
   ```

2. Open the notebook in Jupyter or Kaggle.

3. Make sure you use the dataset from Kaggle:
   ```bash
   /kaggle/input/sf-salaries/Salaries.csv
   ```
