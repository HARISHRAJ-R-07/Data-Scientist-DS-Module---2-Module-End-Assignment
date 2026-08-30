# 🛒 Online Retail Data Analysis

> **Data Science Project | Exploratory Data Analysis | Customer & Sales Insights**

An end-to-end **Online Retail Data Analysis** project using Python to clean, transform, analyze, and visualize real-world retail transaction data.

---

## 📌 Project Overview

This project analyzes an **Online Retail dataset** containing customer transactions, product details, quantities, prices, purchase dates, customer information, and countries.

The main objective is to transform raw retail transaction data into meaningful information through:

* 🧹 Data Cleaning
* 🔧 Feature Engineering
* 📊 Exploratory Data Analysis
* 📈 Statistical Analysis
* 📉 Data Visualization
* 💡 Business Insights

---

## 🎯 Objectives

The project aims to:

* Clean and preprocess real-world retail data
* Handle missing and duplicate records
* Create useful features from transaction data
* Perform exploratory data analysis
* Analyze customer and product behavior
* Identify sales trends and patterns
* Create meaningful visualizations
* Generate business-oriented insights

---

## 📂 Dataset

**Dataset:** Online Retail Dataset – UCI Repository

The dataset contains transaction-level information including:

| Column        | Description                    |
| ------------- | ------------------------------ |
| `InvoiceNo`   | Invoice number                 |
| `StockCode`   | Product/stock code             |
| `Description` | Product description            |
| `Quantity`    | Quantity purchased             |
| `InvoiceDate` | Date and time of transaction   |
| `UnitPrice`   | Price per unit                 |
| `CustomerID`  | Customer identification number |
| `Country`     | Customer's country             |

---

## 🧹 Data Cleaning

The following preprocessing steps were performed:

1. Removed rows with missing `CustomerID`
2. Removed duplicate records
3. Removed records where `Quantity` was not greater than zero
4. Removed records where `UnitPrice` was not greater than zero
5. Prepared the cleaned dataset for further analysis

---

## 🔧 Feature Engineering

New features were created to improve the analysis:

| Feature           | Description                        |
| ----------------- | ---------------------------------- |
| `TotalPrice`      | `Quantity × UnitPrice`             |
| `year`            | Year extracted from `InvoiceDate`  |
| `month`           | Month extracted from `InvoiceDate` |
| `day`             | Day extracted from `InvoiceDate`   |
| `hour`            | Hour extracted from `InvoiceDate`  |
| `CustomerSegment` | Customer segmentation              |
| `OrderSize`       | Classification of order size       |
| `DayType`         | Weekday/Weekend classification     |

---

## 🔍 Exploratory Data Analysis

The following techniques were used:

* `describe()`
* `value_counts()`
* Unique-value analysis
* `groupby()`
* Customer analysis
* Country-wise sales analysis
* Month-wise sales analysis
* Product-wise sales analysis

---

## 📐 Statistical Analysis

The following numerical variables were analyzed:

* Quantity
* Unit Price
* Total Price

Statistical measures include:

* Mean
* Median
* Mode
* Standard deviation
* Variance
* Percentiles

---

## 📊 Data Visualizations

### 📈 Matplotlib

The project includes:

* Total Sales by Month
* Total Sales Box Plot
* Total Sales by Country
* Total Sales Histogram

### 🎨 Seaborn

The project includes:

* Sales by Country Count Plot
* Sales by Customer Segment Violin Plot
* Correlation Heatmap
* Pair Plot

### 💼 Business Insight Visualizations

Additional visualizations were created to analyze:

* Top 10 countries by total sales
* Best-performing sales month
* Peak sales time
* Top 10 products by total sales
* Customer behavior: Quantity vs Total Sales
* High-value customers: Total Spent vs Number of Invoices

---

## 💡 Key Insights

The analysis focuses on identifying:

🔹 **Top Country**
Identify the country contributing the highest total sales.

🔹 **Best Sales Month**
Determine the month with the highest sales performance.

🔹 **Peak Sales Time**
Identify the time of day when sales activity is highest.

🔹 **Top Products**
Identify products generating the highest total sales.

🔹 **Customer Behavior**
Analyze the relationship between customer purchase quantity and total sales.

🔹 **High-Value Customers**
Identify customers with high spending and significant numbers of invoices.

> 📌 Exact numerical values and rankings can be obtained from the executed notebook outputs.

---

## 🛠️ Tools & Technologies

| Technology          | Purpose                   |
| ------------------- | ------------------------- |
| 🐍 Python           | Programming & analysis    |
| 🐼 Pandas           | Data manipulation         |
| 🔢 NumPy            | Numerical analysis        |
| 📊 Matplotlib       | Data visualization        |
| 🎨 Seaborn          | Statistical visualization |
| 📓 Jupyter Notebook | Analysis environment      |
| 💻 VS Code          | Development               |
| 🌿 Git              | Version control           |
| 🐙 GitHub           | Project hosting           |

---

## 📁 Project Structure

```text
online-retail-data-analysis/
│
├── 📂 data/
│   └── cleaned_online_retail.csv
│
├── 📂 notebooks/
│   └── online_retail_analysis.ipynb
│
├── 📂 plots/
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
├── 📄 README.md
├── 📄 requirements.txt
└── 📄 .gitignore
```

---

## ▶️ How to Run the Project

### 1. Clone the repository

```bash
git clone <repository-url>
```

### 2. Open the project in VS Code

```bash
cd online-retail-data-analysis
code .
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Open the notebook

Open:

```text
notebooks/online_retail_analysis.ipynb
```

### 5. Run the notebook

Run the cells sequentially to reproduce the data cleaning, analysis, and visualizations.

---

## 📈 Project Workflow

```text
Raw Retail Data
       ↓
Data Cleaning
       ↓
Feature Engineering
       ↓
Exploratory Data Analysis
       ↓
Statistical Analysis
       ↓
Data Visualization
       ↓
Business Insights
       ↓
Final Results
```

---

## 📝 Conclusion

This project demonstrates an end-to-end **data analysis workflow** using real-world retail transaction data.

The project covers data cleaning, feature engineering, exploratory data analysis, statistical analysis, visualization, and business insight generation using Python.

It provides practical experience in transforming raw transaction data into meaningful analytical results.

---

## 👨‍💻 Author

**Harish Raj**

Data Science Learner | Python | Data Analysis | Machine Learning

---

⭐ **If you find this project useful, consider giving the repository a star!**

