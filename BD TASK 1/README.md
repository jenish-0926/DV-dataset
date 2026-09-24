# TASK 1: SUPERSTORE SALES DATA UNDERSTANDING, CLEANING & EXPLORATORY ANALYSIS

## PROJECT OVERVIEW

This project is about understanding and analyzing the **Superstore Sales dataset** using Python.

The dataset is cleaned and explored to understand sales, categories, dates, delivery time, and missing values. Different charts are also created to understand the data easily.

---

## OBJECTIVES

The main objectives of this project are:

* Load the Superstore Sales dataset.
* Understand the structure of the dataset.
* Display the first few rows of the data.
* Check column names and data types.
* Generate summary statistics.
* Convert Order Date and Ship Date into datetime format.
* Calculate the number of delivery days.
* Check for missing values.
* Find unique values in categorical columns.
* Calculate total sales for each category.
* Create charts to understand the sales data.

---

## TECHNOLOGIES USED

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## DATASET

**Dataset Name:** `SampleSuperstore.csv`

The dataset contains information about:

* Orders
* Customers
* Products
* Categories
* Sales
* Profit
* Quantity
* Discount
* Shipping details

---

## PROJECT WORKFLOW

### STEP 1: IMPORT LIBRARIES

Import the Python libraries needed for data analysis and visualization.

### STEP 2: LOAD THE DATASET

Load the `SampleSuperstore.csv` file using Pandas.

### STEP 3: VIEW THE FIRST FIVE ROWS

Use `head()` to display the first five rows of the dataset.

### STEP 4: CHECK DATASET INFORMATION

Use `info()` to check:

* Column names
* Number of rows
* Data types
* Non-null values

### STEP 5: VIEW SUMMARY STATISTICS

Use `describe()` to get basic statistics such as:

* Count
* Mean
* Minimum
* Maximum
* Standard deviation

### STEP 6: CONVERT DATE COLUMNS

Convert **Order Date** and **Ship Date** into datetime format.

This makes it easier to perform date calculations.

### STEP 7: CHECK DATE DATA TYPES

Check the data types again to make sure the date columns were converted correctly.

### STEP 8: CALCULATE DELIVERY DAYS

Create a new column called **Delivery Days**.

It shows the number of days between the Order Date and Ship Date.

### STEP 9: VIEW THE UPDATED DATA

Display the dataset again to check the new **Delivery Days** column.

### STEP 10: CHECK UNIQUE VALUES

Find the unique values in the **Category** column.

This helps us understand the different product categories in the dataset.

### STEP 11: CHECK MISSING VALUES

Use `isnull().sum()` to find missing values in each column.

### STEP 12: CALCULATE TOTAL SALES BY CATEGORY

Calculate the total sales for each product category.

This helps us understand how much each category contributes to total sales.

### STEP 13: CREATE CATEGORY-WISE SALES CHART

Create a **bar chart** to compare sales between different categories.

### STEP 14: CREATE SALES DISTRIBUTION CHART

Create a **histogram** to understand how the sales values are distributed.

---

## VISUALIZATIONS

The following charts are created:

### 1. Bar Chart – Total Sales by Category

Shows the total sales for each product category.

### 2. Histogram – Sales Distribution

Shows how the sales values are distributed across the dataset.

---

## KEY OUTCOMES

After completing this project:

* The Superstore dataset was successfully loaded and explored.
* The structure and data types of the dataset were understood.
* Date columns were converted into datetime format.
* Delivery days were calculated.
* Missing values were checked.
* Unique category values were identified.
* Summary statistics were generated.
* Total sales by category were calculated.
* Bar charts and histograms were created to understand the data visually.

---

## CONCLUSION

This project helped us understand the **Superstore Sales dataset** using Python. Data cleaning, basic analysis, and visualization were performed to find useful information about sales and product categories.
