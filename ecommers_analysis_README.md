# E-Commerce Sales Analysis

## Project Overview

This project is an e-commerce sales analysis project created using Python. The notebook takes sales data from a CSV file, cleans the data, calculates revenue-related values, performs different types of analysis, and creates charts to understand the results.

The main goal of the project is to understand sales performance and find useful information from the available e-commerce data.

## Tools and Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Dataset

The project uses a CSV file named `ecommerce_sales.csv`.

The analysis works with information such as:

- Order Date
- Customer Name
- Gender
- Age
- City
- Category
- Product
- Quantity
- Unit Price
- Payment Mode
- Discount
- Rating

## Project Workflow

### 1. Load the Data

The dataset is loaded using Pandas:

```python
df = pd.read_csv("data/ecommerce_sales.csv")
```

### 2. Explore the Data

The notebook checks the data using:

- `head()`
- `shape`
- `isnull().sum()`
- `duplicated().sum()`

This helps understand the dataset and check whether it contains missing or duplicate records.

### 3. Clean the Data

Duplicate records are removed from the dataset.

The `Order_Date` column is also converted into a proper date format so that it can be used for monthly analysis.

### 4. Calculate Sales and Revenue

The project calculates Gross Sales using:

```python
Gross_Sales = Quantity * Unit_Price
```

The discount amount is calculated using:

```python
Discount_Amount = Gross_Sales * Discount / 100
```

Revenue is then calculated as:

```python
Revenue = Gross_Sales - Discount_Amount
```

### 5. Sales Analysis

The notebook calculates important sales metrics, including:

- Total Revenue
- Highest Order Value
- Lowest Order Value
- Average Revenue
- Total Quantity Sold
- Average Order Value
- Average Customer Rating

The results from the notebook include:

- Total Revenue: 480775
- Highest Order Value: 54000
- Lowest Order Value: 5950
- Average Revenue: 24038.75
- Total Quantity Sold: 50
- Average Order Value: 24038.75
- Average Rating: 4.32

## Analysis Performed

### Category-wise Revenue

Revenue is grouped by product category and sorted from highest to lowest.

This helps identify which product category contributes the most revenue.

### Product-wise Quantity

The project calculates the total quantity sold for each product.

This helps understand which products are being sold in larger quantities.

### City-wise Revenue

Revenue is grouped by city to compare sales performance across different locations.

### Payment Mode Analysis

The project counts orders according to payment mode.

This helps understand which payment methods are used most frequently.

### Customer Revenue Analysis

Revenue is grouped by customer name and the top five customers are identified based on revenue.

### Age Group Analysis

Customers are divided into different age groups:

- Under 18
- 18-25
- 26-35
- 36-50
- 50+

Revenue is then analyzed for each age group.

### Product Summary

A product summary is created containing:

- Total Quantity
- Total Revenue
- Average Rating

The products are sorted according to total revenue.

### Correlation Analysis

The project creates a correlation matrix for:

- Age
- Quantity
- Unit Price
- Discount
- Rating
- Revenue

This helps understand the relationships between numerical columns.

## Visualizations

The notebook creates several visualizations using Matplotlib:

1. Revenue by Category
2. Revenue by City
3. Monthly Revenue Trend
4. Payment Method Distribution
5. Top 5 Customers by Revenue
6. Revenue by Age Group
7. Correlation Matrix

These charts make the analysis easier to understand and help identify patterns in the data.

## Key Findings

Based on the notebook results:

- Total revenue is 480775.
- The highest order value is 54000.
- The lowest order value is 5950.
- Total quantity sold is 50.
- The average customer rating is 4.32.
- Laptop has the highest total revenue among the products in the analysis.
- Customer revenue is used to identify the top five customers.
- Monthly revenue is analyzed to understand sales trends.
- Payment modes are compared using order counts.

## Project Objective

The objective of this project is to practice the complete data analysis process using Python:

1. Load the data
2. Explore the data
3. Clean the data
4. Create calculated columns
5. Analyze the data
6. Find useful business information
7. Create visualizations

## Conclusion

This project demonstrates how Python can be used to analyze e-commerce sales data.

It combines data cleaning, calculations, grouping, statistical analysis, and visualization to understand different aspects of sales performance.

The project is suitable as a beginner-level Data Analytics project for learning Pandas, NumPy, Matplotlib, and basic business data analysis.
