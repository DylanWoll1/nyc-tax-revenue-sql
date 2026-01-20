This project analyzes NYC tax revenue data using MySQL. Raw public data is loaded into a staging table, transformed into a star schema, and queried to evaluate fiscal-year trends, year-over-year changes, and tax source contributions, with a focus on Sales and Use Tax.

# NYC Tax Revenue Analysis (SQL, MySQL)

## Overview
End-to-end SQL analytics project using NYC Open Data (Tax Revenue Actuals). Built a star schema in MySQL, loaded raw data into staging, transformed into analytics tables, and produced revenue trend insights focused on Sales and Use Tax.

## Dataset
NYC Open Data: Tax Revenue Actuals (NYC)  
[New_York_City_Tax_Revenue_Actuals.csv](https://github.com/user-attachments/files/24725396/New_York_City_Tax_Revenue_Actuals.csv)


## What’s in this repo
- `schema/` – DDL for staging + star schema, plus EER diagram image
- `queries/` – data quality checks, transformations, and analysis queries
- `docs/` – business questions and definitions
- `insights/` – written findings and recommendations

## How to run
1. Run `schema/schema.sql` to create tables
2. Import CSV into `stg_tax_revenue_actuals` (Workbench Import Wizard)
3. Run transformation + analysis SQL in `queries/` (top to bottom)

## Key questions answered
See `docs/business_questions.md`

## Skills demonstrated
SQL (CTEs, window functions), data modeling (star schema), data quality validation, fiscal trend analysis
