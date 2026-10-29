# Retail Customer Shopping Behavior & Sales Insights

## 📌 Project Overview

An end-to-end data analytics project that explores retail customer shopping behavior using **Python, PostgreSQL, SQL, and Microsoft Power BI**.

The project analyzes purchasing patterns, product category performance, customer segments, discount usage, subscription behavior, shipping preferences, and customer ratings to generate actionable business insights.

## 🎯 Business Problem

Retail businesses need to understand customer purchasing behavior to improve product offerings, customer engagement, and promotional strategies.

This project analyzes customer shopping data to identify spending patterns, compare customer segments, evaluate discount usage, and support data-driven business decisions.

## 🎯 Project Objectives

- Analyze purchase amounts across product categories and individual items.
- Compare purchasing behavior across customer segments.
- Examine subscription status and discount usage.
- Explore customer ratings and shipping preferences.
- Identify popular payment methods and shopping patterns.
- Develop an interactive Power BI dashboard for business reporting.

## 🛠️ Tools and Technologies

| Tool | Purpose |
|---|---|
| Python | Data processing and analysis |
| Pandas & NumPy | Data cleaning and transformation |
| Matplotlib | Exploratory data visualization |
| Jupyter Notebook | Interactive analysis and documentation |
| PostgreSQL | Data storage and querying |
| SQL | Business analysis and insight generation |
| Microsoft Power BI | Interactive dashboard development |
| Git & GitHub | Version control and project documentation |

## 🔄 Project Workflow

### 1. Data Understanding
- Inspected dataset structure, dimensions, and column names.
- Reviewed data types and descriptive statistics.
- Identified missing values and potential data quality issues.

### 2. Data Cleaning
- Checked for duplicate records.
- Handled missing customer review ratings.
- Standardized column names.
- Validated numerical and categorical values.
- Prepared the dataset for further analysis.

### 3. Exploratory Data Analysis (EDA)
- Analyzed purchase amounts across product categories.
- Examined customer ratings and purchasing preferences.
- Compared subscription and discount usage patterns.
- Explored customer age groups and shopping frequency.

### 4. Feature Engineering
- Created customer age groups for segmentation.
- Mapped purchase-frequency categories to approximate day intervals.
- Prepared additional fields for SQL analysis and dashboard reporting.

### 5. SQL Analysis with PostgreSQL

Used SQL techniques to answer business questions, including:
- Aggregate functions such as `SUM()`, `AVG()`, and `COUNT()`.
- Conditional logic using `CASE WHEN`.
- Common Table Expressions (CTEs).
- Subqueries and window functions.
- Grouping, filtering, and ranking.

### 6. Power BI Dashboard Development
- Created KPI cards for key shopping metrics.
- Compared purchase amounts across product categories.
- Analyzed customer segments and age groups.
- Examined subscription and discount usage.
- Visualized customer ratings and shipping preferences.
- Added interactive slicers and filters.

### 7. Data Validation

Compared key metrics across Python, PostgreSQL, and Power BI to ensure consistency and reporting accuracy.

## 📊 Key Business Questions

1. Which product categories generate the highest total purchase amounts?
2. Which items receive the highest average customer ratings?
3. How does average spending differ between subscribed and non-subscribed customers?
4. Which products have the highest proportion of discounted records?
5. How does purchase amount vary across customer age groups?
6. Which shipping methods and payment methods are most commonly used?
7. How do customer segments differ in their shopping behavior?
8. What patterns can be observed in purchase frequency and customer preferences?

## 📈 Dashboard Preview

![Retail Customer Shopping Behavior Dashboard](images.png)

## 💡 Key Findings

Key findings are derived from SQL analysis and Power BI visualizations, focusing on category performance, customer spending patterns, and discount usage.

## ⚠️ Limitations

- The dataset does not contain transaction dates, so time-based sales trends and growth cannot be calculated.
- Product costs are unavailable, so profitability and profit margins cannot be measured.
- Explicit discount amounts are unavailable, limiting the analysis of discount value and financial impact.
- Purchase amount is used as a spending measure rather than a time-based sales metric.
- The analysis describes observed relationships and patterns; it does not establish causation.
- Purchase-frequency categories mapped to day intervals are approximate representations, not verified transaction intervals.

## 🚀 How to Run the Project

### Prerequisites
- Python 3.x
- Jupyter Notebook
- PostgreSQL
- Microsoft Power BI Desktop
- Git

### 1. Clone the Repository

```bash
git clone <your-github-repository-url>
cd Retail-Customer-Shopping-Behavior
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the Python Notebook

- Open Jupyter Notebook.
- Navigate to the `notebooks/` directory.
- Open the analysis notebook.
- Configure the dataset path.
- Run the cells to perform data cleaning, feature engineering, and exploratory data analysis.

### 4. Load Data into PostgreSQL

- Create a PostgreSQL database.
- Create a table matching the cleaned dataset's columns and data types.
- Import the cleaned data.
- Execute the SQL scripts in the `sql/` directory.

### 5. Open the Power BI Dashboard

- Open the `.pbix` file in Power BI Desktop.
- Configure the data source and database connection.
- Refresh the data.
- Explore the dashboard using its filters and slicers.

## 🧠 Skills Demonstrated

- Data Cleaning and Preprocessing
- Data Transformation and Feature Engineering
- Exploratory Data Analysis (EDA)
- Python, Pandas, NumPy, and Matplotlib
- SQL and PostgreSQL
- Common Table Expressions (CTEs)
- Subqueries and Window Functions
- Customer Segmentation
- KPI Analysis and Business Reporting
- Power BI Dashboard Development
- Data Validation
- Git and GitHub

## 👨‍💻 Project Purpose

This project demonstrates an end-to-end data analytics workflow, from raw data preparation and SQL-based business analysis to interactive dashboard development.

It showcases the ability to transform customer shopping data into meaningful insights that support retail business decisions.
