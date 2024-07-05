# Walmart Sales Analysis Project

## Project Overview
This project aims to gain insights into Walmart's sales data from three branches located in Mandalay, Yangon, and Naypyitaw. The primary objective is to understand various factors influencing sales performance across different branches.

## Data Description
The dataset, obtained from the Kaggle Walmart Sales Forecasting Competition, contains sales transactions from the three branches. It includes 17 columns and 1000 rows with the following attributes:

- **invoice_id**: Invoice of the sales made (VARCHAR)
- **branch**: Branch at which sales were made (VARCHAR)
- **city**: Location of the branch (VARCHAR)
- **customer_type**: Type of customer (VARCHAR)
- **gender**: Gender of the customer (VARCHAR)
- **product_line**: Product line of the product sold (VARCHAR)
- **unit_price**: Price of each product (DECIMAL)
- **quantity**: Amount of product sold (INT)
- **VAT**: Tax amount on the purchase (FLOAT)
- **total**: Total cost of the purchase (DECIMAL)
- **date**: Date of the purchase (DATE)
- **time**: Time of the purchase (TIMESTAMP)
- **payment_method**: Payment method used (DECIMAL)
- **cogs**: Cost of goods sold (DECIMAL)
- **gross_margin_percentage**: Gross margin percentage (FLOAT)
- **gross_income**: Gross income (DECIMAL)
- **rating**: Customer rating (FLOAT)

## Analysis Goals
1. **Product Analysis**:
   - Understand different product lines.
   - Identify best and underperforming product lines.

2. **Sales Analysis**:
   - Analyze sales trends and measure effectiveness of sales strategies.
   - Identify modifications needed to boost sales.

3. **Customer Analysis**:
   - Uncover customer segments and purchase trends.
   - Assess profitability of each customer segment.

## Approach
1. **Data Wrangling**:
   - Inspect and clean data to handle NULL and missing values.
   - Create a database, build tables, and insert data.
   - Ensure no NULL values by setting NOT NULL constraints.

2. **Feature Engineering**:
   - Add `time_of_day` column to analyze sales in different parts of the day.
   - Add `day_name` column to analyze sales by day of the week.
   - Add `month_name` column to analyze sales by month.

3. **Exploratory Data Analysis (EDA)**:
   - Conduct analysis to answer key business questions and project aims.

## Key Business Questions
- **Generic Questions**:
  - How many unique cities are in the data?
  - In which city is each branch located?

- **Product Analysis**:
  - How many unique product lines are there?
  - What is the most common payment method?
  - Which product line has the highest sales and revenue?
  - Which city has the largest revenue?
  - How do product lines perform based on average sales?

- **Sales Analysis**:
  - What are the sales trends by time of day and day of the week?
  - Which customer type generates the most revenue?
  - Which city has the highest tax percentage?
  - What is the average rating of each product line?

- **Customer Analysis**:
  - How many unique customer types and payment methods exist?
  - Which customer type buys the most?
  - What is the gender distribution across branches?
  - When do customers provide the most ratings?

## Tools and Technologies
- **SQL**: Database management and querying
- **Python**: Data analysis and visualization
- **Excel**: Data cleaning and feature engineering
- **Tableau**: Creating visual dashboards for insights presentation

## Conclusion
This project provided valuable insights into Walmart's sales data, highlighting key trends and areas for improvement. The analysis helped in understanding customer behavior, product performance, and sales patterns, aiding in strategic decision-making to enhance sales and profitability.

