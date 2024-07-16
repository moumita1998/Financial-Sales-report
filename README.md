
# Sales & Financial Report

Generated sales and Financial report of AtliQ Hardware based on their FY 2019, 2020 and 2021 data.


## Table Of Content
- [Introduction](#introduction)
- [Objective](#Objective)
- [Data Sources](#DataSources)
- [Tools & Technologies](#installation)
- [Methodology](#methodology)


## Introduction
A comprehensive Excel project designed to analyze sales and financial data, generate automated reports, and provide actionable insights for a Hardware Company. 

## Objectives
- To analyze historical sales data and identify trends.
- To generate financial reports for performance evaluation.
- To automate data processing and report generation to save time   and reduce errors.

## Data Sources
- Customer data: Customer Info such customer ID, Name, Market, platform, channel and distributor.
- Market data:Market, subzone and region.
- Product data: Product code, division, segment, category
- Monthly sales:
- Target 2021:

## Tools and Technologies
- Microsoft Excel: Used for data manipulation, analysis, and visualization.
- Power Query: For data extraction, transformation, and loading (ETL).
- Excel Formulas and Functions: For data analysis and calculations.

## Methodology

1. Perform ETL: Import different CSV files Excel using Power Query.
Handle missing values by using Power Query's data cleaning functions.
Ensure all dimension tables (e.g., Products, Regions) have unique IDs.
Manage errors or #N/A columns using Power Query's error-handling capabilities.
Check and correct spelling errors to maintain data consistency.

Load Data:
Create connections only and load the data into the data model for efficient processing and analysis.

2. Data Modeling
Create Relationships:

Established relationships between tables (e.g., customer, product, monthly sales) in the data model to enable comprehensive analysis.

3. Create Date Table: Used Power Query to generate a new Date table. Created condtional and custom columns for year, month, day, fiscal month, and fiscal year using DAX functions and other excel formulas.
Define Fiscal Year:
Create a fiscal year calculation based on the company's fiscal year starting in September.
Calculate the fiscal month and extract the corresponding fiscal year using Power Query transformations.

3. Power pivot: Created pivot table using power pivot comparing net sales in FY 2019, 2020, 2021. Comparing sales performance in 20 vs 21.

4. Measures Using DAX Functions: Created sales metrics and financial metrics using DAX function

5. Format Report Using Conditional Formatting: Apply conditional formatting to highlight key metrics.Used color scales to represent sales performance and financial status visually.Highlight outliers or exceptional values using data bars or icon sets.

### Customer Sales Report Image:
![image](https://github.com/user-attachments/assets/79345c77-38e5-43e4-89d3-1c1601472ec4)

### Market Performance VS target:
![image](https://github.com/user-attachments/assets/85f3ddd3-4ea2-45ab-8629-8aa2082fbd2b)

