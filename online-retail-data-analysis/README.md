# Online Retail Data Analysis

## Project Description

This project analyzes an Online Retail dataset containing customer transactions, product details, quantities, prices, purchase dates, customer information, and countries.

The objective is to clean and preprocess real-world retail data, perform exploratory data analysis (EDA), create new features, visualize sales patterns, and generate business insights.

## Objectives

- Clean and preprocess real-world data
- Perform exploratory data analysis (EDA)
- Create new features for analysis
- Visualize trends using charts
- Generate business insights

## Dataset

**Dataset:** Online Retail Dataset – UCI Repository

The notebook works with the following fields:

- InvoiceNo
- StockCode
- Description
- Quantity
- InvoiceDate
- UnitPrice
- CustomerID
- Country

## Data Cleaning

The notebook performs the following cleaning steps:

1. Removes rows with missing `CustomerID`.
2. Removes duplicate rows.
3. Removes rows where `Quantity` is not greater than zero.
4. Removes rows where `UnitPrice` is not greater than zero.

## Feature Engineering

The following features are created:

- `TotalPrice` = Quantity × UnitPrice
- `year`
- `month`
- `day`
- `hour`
- `CustomerSegment`
- `OrderSize`
- `DayType`

## Exploratory Data Analysis

The project uses:

- `describe()`
- `value_counts()`
- `unique()` / unique-value analysis
- `groupby()`
- Top customer analysis
- Country-wise sales analysis
- Month-wise sales analysis
- Product-wise sales analysis

## Statistical Analysis

The project analyzes:

- Quantity
- UnitPrice
- TotalPrice

Statistics include:

- Mean
- Median
- Mode
- Standard deviation
- Variance
- Percentiles

## Visualizations

### Matplotlib

- Line chart – Total Sales by Month
- Box plot – Total Sales
- Bar chart – Total Sales by Country
- Histogram – Total Sales

### Seaborn

- Count plot – Sales by Country
- Violin plot – Sales by Customer Segment
- Correlation heatmap
- Pair plot

### Business Insight Visualizations

- Top 10 countries by total sales
- Best sales month
- Peak sales time
- Top 10 products by total sales
- Customer behavior: Quantity vs Total Sales
- High-value customers: Total Spent vs Number of Invoices

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- VS Code
- Git
- GitHub

## Project Structure

```text
online-retail-data-analysis/
│
├── data/
│   └── cleaned_online_retail.csv
│
├── notebooks/
│   └── online_retail_analysis.ipynb
│
├── plots/
│   ├── sales_by_month.png
│   ├── box_plot_total_sales.png
│   ├── sales_by_country.png
│   ├── histogram_total_sales.png
│   ├── count_sales_by_country.png
│   ├── violin_sales_customer_segment.png
│   ├── correlation_heatmap.png
│   ├── pairplot.png
│   ├── top_10_countries.png
│   ├── best_sales_month.png
│   ├── peak_sales_time.png
│   ├── top_10_products.png
│   ├── customer_behavior_quantity_vs_sales.png
│   └── high_value_customers.png
│
├── README.md
├── requirements.txt
└── .gitignore
```

## Key Insights

The notebook is designed to identify:

- The top country by total sales
- The best-performing sales month
- The peak sales time during the day
- Top-performing products
- Customer purchasing behavior
- High-value customers

The exact numerical values should be taken from the executed notebook outputs.

## Conclusion

This project demonstrates an end-to-end data analysis workflow using real-world retail transaction data, including data cleaning, feature engineering, exploratory analysis, statistical analysis, visualization, and business insight generation.
