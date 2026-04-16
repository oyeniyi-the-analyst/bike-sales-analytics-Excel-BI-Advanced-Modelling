# Data Preparation

The dataset was transformed into a structured Excel table for analysis.

## Key Steps

- Converted raw data into Excel Table format
- Validated data types (dates, currency, numeric fields)
- Checked for missing values and inconsistencies
- Performed duplicate analysis using pivot tables

## Calculated Columns

- Profit Margin = Profit / Revenue
- Average Order Value = Revenue / Order Quantity
- Year-Month for time-based analysis
- Quarter for seasonal grouping

## Data Quality Approach

Duplicate records were analyzed using pivot tables. Only exact duplicates across all fields were removed. All valid transactional records were preserved to maintain analytical integrity.