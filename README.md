# E-Commerce Sales & Profitability Analysis

## Project Overview

This project analyzes Superstore sales data to understand sales performance, profitability, customer segments, product categories, regions, discounts, and overall business performance.

The project uses Python for data cleaning, exploratory data analysis, and visualization, and Power BI for creating an interactive business dashboard.

## Objectives

- Analyze sales and profit performance.
- Clean and prepare the Superstore dataset.
- Perform exploratory data analysis using Python.
- Identify high-performing categories and regions.
- Analyze the relationship between discount and profit.
- Identify the top 10 products by sales.
- Create an interactive Power BI dashboard.
- Provide business insights and recommendations.

## Dataset

The project uses the Superstore sales dataset.

The dataset contains information such as:

- Order ID
- Order Date
- Ship Date
- Customer information
- Product Name
- Category
- Region
- Segment
- Sales
- Quantity
- Discount
- Profit

## Tools Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Power BI
- Git
- GitHub

## Data Preparation

The following data preparation steps were performed:

1. Loaded the Superstore CSV dataset.
2. Inspected the dataset structure.
3. Checked missing values.
4. Checked duplicate records.
5. Converted Order Date and Ship Date into date format.
6. Created Year and Month fields.
7. Calculated Shipping Days.
8. Calculated Profit Margin.
9. Saved the cleaned dataset as `cleaned_superstore.csv`.

## Exploratory Data Analysis

The analysis included:

- Descriptive statistics.
- Total sales.
- Total profit.
- Total quantity.
- Total orders.
- Sales by category.
- Profit by category.
- Sales by region.
- Profit by region.
- Sales by segment.
- Profit by segment.
- Correlation analysis.
- Sales outlier analysis.

## Visualizations

Six visualizations were created:

1. Monthly Sales Trend
2. Sales by Category
3. Profit by Category
4. Sales by Region
5. Discount vs Profit
6. Top 10 Products by Sales

## Power BI Dashboard

The Power BI dashboard contains:

### KPI Cards

- Total Sales
- Total Profit
- Total Orders
- Profit Margin

### Charts

- Sales by Category
- Profit by Category
- Sales by Region
- Discount vs Profit
- Top 10 Products by Sales

### Interactive Slicers

- Year
- Region
- Category
- Segment

## Key Business Insights

1. Technology is the highest-performing category in terms of sales and contributes strongly to overall profit.

2. Furniture has comparatively lower profitability, indicating the need to review pricing, costs, and discounts.

3. The West region records the highest sales among the regions.

4. Office Supplies is an important contributor to overall business profitability.

5. Discount levels can influence profitability, so excessive discounting should be carefully controlled.

## Business Recommendations

### 1. Focus on High-Performing Products

The business should continue investing in high-performing Technology and other profitable products through effective promotions and inventory planning.

### 2. Control Discounts and Improve Furniture Profitability

The company should review discount policies and pricing strategies, especially for products with lower profitability.

## Project Structure

```text
superstore-sales-analytics
│
├── data
│   ├── Sample-Superstore.csv
│   └── cleaned_superstore.csv
│
├── python
│   └── Superstore_Analysis.ipynb
│
├── visualizations
│   ├── monthly_sales_trend.png
│   ├── sales_by_category.png
│   ├── profit_by_category.png
│   ├── sales_by_region.png
│   ├── discount_vs_profit.png
│   └── top_10_products_by_sales.png
│
├── powerbi
│   └── Superstore_Dashboard.pbix
│
├── presentation
│   └── Superstore_Presentation.pptx
│
└── README.md
