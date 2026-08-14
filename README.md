# Employee Salary Analysis System

## 📌 Project Overview

The **Employee Salary Analysis System** is a Python-based data analysis project that uses **NumPy** to analyze employee salary, department, and experience data.

The project contains data for **20 employees** and performs basic salary analysis, filtering, salary calculations, and employee identification based on department and experience.

## 🛠️ Technologies Used

- Python
- NumPy
- Jupyter Notebook

## 📊 Dataset

The project uses the following employee information:

- Employee ID
- Department
- Salary
- Experience (in years)

The dataset contains **20 employees** across departments such as:

- IT
- HR
- Sales
- Finance
- Marketing

## 🔍 Analysis Performed

The project performs the following analyses:

1. **Total Employees**
   - Total number of employees: **20**

2. **Average Salary**
   - Average salary: **₹51,850**

3. **Highest Salary**
   - Highest salary: **₹75,000**

4. **Lowest Salary**
   - Lowest salary: **₹35,000**

5. **Median Salary**
   - Median salary: **₹50,500**

6. **Standard Deviation**
   - Standard deviation of salary: approximately **₹11,145.74**

7. **Employees Earning Above ₹60,000**
   - Identifies salaries greater than ₹60,000.

8. **Employees Earning Below ₹40,000**
   - Identifies salaries below ₹40,000.

9. **10% Salary Increment**
   - Calculates the salary after applying a 10% increment.

10. **5% Tax Calculation**
    - Calculates 5% tax on employee salaries.

11. **Net Salary**
    - Calculates salary after deducting 5% tax.

12. **IT Department Employees**
    - Filters salaries of employees working in the IT department.

13. **Employees With More Than 5 Years Experience**
    - Identifies employee IDs of employees having more than 5 years of experience.

## 💻 Example Code

```python
import numpy as np

# Average Salary
print("Average Salary:", np.mean(salary))

# Highest Salary
print("Highest Salary:", np.max(salary))

# Lowest Salary
print("Lowest Salary:", np.min(salary))

# Median Salary
print("Median Salary:", np.median(salary))

# Employees earning above ₹60,000
high_salary = salary[salary > 60000]
print(high_salary)

# 10% salary increment
increment = salary * 1.10
print(increment)

# 5% tax
tax = salary * 0.05
print(tax)

# Net salary
net_salary = salary - tax
print(net_salary)

# IT department employees
it_salary = salary[department == "IT"]
print(it_salary)
```

## 📁 Project Structure

```text
Employee-Salary-Analysis-System/
│
├── Employee Salary Analysis System.ipynb
└── README.md
```

## 🎯 Project Objective

The main objective of this project is to practice **NumPy arrays, statistical calculations, filtering, conditional indexing, and basic employee salary analysis** using Python.

## 📈 Key Learning Outcomes

Through this project, you can learn:

- Creating NumPy arrays
- Working with numerical data
- Calculating mean, median, maximum, and minimum
- Calculating standard deviation
- Filtering data using conditions
- Performing arithmetic operations on arrays
- Working with multiple related arrays
- Extracting data based on department and experience

## 👨‍💻 Author

**Employee Salary Analysis System**

Built using Python and NumPy for data analysis practice.
