# EDA
This project is an Exploratory Data Analysis(EDA) of the Superstore Sales Dataset from kaggle https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting/data.  
It includes data loading(with fallback parsing from malformed CSVs), cleaning, feature engineering, trend analysis, general visualizations of key business metrics and some final business insights.

## Features
- Robust CSV loader that can fix malformed Superstore files (commas inside product names, misaligned columns, etc.).
- Initial dataset exploration (`head`, `info`, `describe`).
- Data cleaning and type conversions (dates, sales, postal codes).
- Feature engineering (time-based variables, average order value, loyalty inference).
- High-level trend analysis:
  - Total sales by year and month
  - Year-over-year and month-over-month growth
  - Refund detection and rates
- Segmentation:
  - Top regions, states, categories, sub-categories, products
  - Customer loyalty (explicit or inferred from repeat orders)
- Pivot tables and KPIs with conditional formatting
- Visualizations:
  - Sales distributions
  - Correlation heatmaps
