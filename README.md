## FinRatioAnalyzer_Mohan-Zhu
The user can use this tool to select data from WRDS to calculate ROA, ROE, current ratio and quick ratio about a company. Besides, this tool can make comments about this company based on the calculation results. The line graph of recent 10 years can also be created

# 1. Project Purpose and the Target Users
The target audience of this project is professional financial data analysts or business students at universities. This project provides a convenient way to filter data, perform calculations based on financial formulas, and generate simple comments based on the calculated results.

# 2. Data Source
Wharton Research Data Services (WRDS)
Access date: 2026-04-20
Period: 2010-2023

# 3. Methods (Python Workflow)
Import Pandas for financial data filtering, table processing, data cleaning, and calculations, and import WRDS to directly pull corporate financial statement data from the database.

Using the calculate_ratio() function, we standardize the calculation logic, handle exceptional cases (such as division by zero), and ensure a standardized output format.

Interact with the user to input the company and the year to be analyzed.

Connect with WRDS database. Using the user's own account.

Using SQL to precisely extract the corporate financial statement data required for analysis from the WRDS database.

Using the predefined calculate_ratio() function and the extracted financial data, we compute and display key financial ratios.

Based on the calculated data and market average benchmarks, we provide a brief evaluation.

The data of these four aspects in the recent 10 years can also be presented as line graphs.
