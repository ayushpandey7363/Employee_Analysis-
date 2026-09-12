# Employee Salary Analysis System

## Overview

This project is a simple Employee Salary Analysis System built with Python and NumPy. It uses employee data to perform basic salary and experience analysis.

The project is designed to practice NumPy arrays, filtering, calculations, and statistical functions.

## Dataset

The notebook contains data for 20 employees.

The dataset includes four main fields:

- Employee ID
- Department
- Salary
- Experience

The departments included in the dataset are IT, HR, Sales, Finance, and Marketing.

## Technology Used

- Python
- NumPy
- Jupyter Notebook

## Analysis Performed

The notebook performs the following analysis:

### 1. Total Employees

Counts the total number of employees in the dataset.

### 2. Average Salary

Calculates the average salary of all employees using NumPy.

### 3. Highest Salary

Finds the highest salary in the dataset.

### 4. Lowest Salary

Finds the lowest salary in the dataset.

### 5. Median Salary

Calculates the median salary of the employees.

### 6. Standard Deviation

Calculates the standard deviation of salaries to understand the variation in salary values.

### 7. Employees Earning Above ₹60,000

Filters the salary array and displays salaries greater than ₹60,000.

### 8. Employees Earning Below ₹40,000

Filters the salary array and displays salaries below ₹40,000.

### 9. 10% Salary Increment

Calculates the salary after giving every employee a 10% increment.

The calculation used is:

```text
New Salary = Salary × 1.10
```

### 10. 5% Tax Calculation

Calculates 5% tax on the original salary.

The calculation used is:

```text
Tax = Salary × 0.05
```

### 11. Net Salary

Calculates salary after deducting the 5% tax.

The calculation used is:

```text
Net Salary = Salary - Tax
```

### 12. IT Department Employees

Filters the salary data to display salaries of employees who belong to the IT department.

### 13. Employees with More Than 5 Years of Experience

Filters employee IDs and displays the employees whose experience is greater than 5 years.

## Project Workflow

The project follows a simple data analysis process:

1. Create NumPy arrays for employee IDs, departments, salaries, and experience.
2. Calculate basic salary statistics.
3. Filter employees based on salary conditions.
4. Calculate salary increments and tax.
5. Calculate net salary.
6. Filter employees by department.
7. Find employees based on years of experience.

## Objective

The main objective of this project is to understand how NumPy can be used to store, filter, and analyze employee data.

This project also provides practice with statistical functions such as mean, median, minimum, maximum, and standard deviation, along with NumPy conditional filtering and arithmetic operations.

## How to Run

1. Open the `Employee Salary Analysis System(1).ipynb` file in Jupyter Notebook or JupyterLab.
2. Make sure NumPy is installed.
3. Run the cells from top to bottom.
4. Check the output of each analysis.

## Conclusion

This project demonstrates a basic employee salary analysis using Python and NumPy. It covers common operations that are useful when working with numerical data, including statistical calculations, filtering, salary calculations, department-based filtering, and experience-based filtering.
