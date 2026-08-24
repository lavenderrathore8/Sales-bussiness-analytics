# Sales Data Analysis & Business Dashboard

A Python-based sales analytics project that analyzes sales performance across products, categories, regions, and months. The project uses Pandas for data analysis and generates summary datasets and visual insights for business decision-making.

## Project Overview

This project analyzes a sales dataset containing 500 records and 10 variables, including date, product, category, region, quantity, sales, cost, and profit.

The analysis focuses on identifying sales trends, top-performing products, category performance, regional performance, and profitability.

## Objectives

- Analyze overall sales and profit performance
- Study monthly sales trends
- Identify top-performing products
- Compare sales across categories
- Analyze regional sales performance
- Evaluate profit and profit margins
- Generate data-driven business insights

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook / Google Colab
- Power BI
- CSV

## Dataset

The dataset contains the following fields:

| Column | Description |
|---|---|
| Date | Transaction date |
| Product | Product name |
| Category | Product category |
| Region | Sales region |
| Quantity | Quantity sold |
| Unit_Price | Price per unit |
| Sales | Total sales value |
| Cost | Product cost |
| Profit | Profit generated |
| Month | Month of transaction |

## Project Workflow

1. Load the sales dataset
2. Clean and prepare the data
3. Perform exploratory data analysis
4. Analyze monthly sales
5. Analyze product performance
6. Analyze category performance
7. Analyze regional performance
8. Analyze profit and profitability
9. Export analysis results as CSV files
10. Create a dashboard for visualization

## Key Analysis

### Monthly Sales Analysis

Sales are grouped by month to identify changes and trends in business performance over time.

### Product Analysis

Products are compared based on their total sales to identify the highest-performing products.

### Category Analysis

Sales and profitability are analyzed across different product categories.

### Regional Analysis

Sales performance is compared across different geographical regions.

### Profit Analysis

Profit is calculated using:

`Profit = Sales - Cost`

Profit margins are also analyzed to understand the profitability of different categories.

## Project Outputs

The project generates the following analysis files:

```text
results/
├── monthly_sales.csv
├── product_analysis.csv
├── category_analysis.csv
├── region_analysis.csv
└── project_summary.csv
