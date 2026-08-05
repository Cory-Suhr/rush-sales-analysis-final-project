 Rush Sales Analysis

## Business Problem

Company leadership wants to better understand sales performance across products, retailers, locations, and sales channels to identify trends, evaluate business performance, and uncover opportunities for future growth.

The objective of this project is to transform raw transactional sales data into meaningful business insights through data preparation, exploratory data analysis (EDA), and executive-level visualizations that support data-driven decision making.

---

## Project Overview

This project analyzes retail sales data from 2020 and 2021 using Python, Pandas, and Matplotlib. The analysis follows a structured data analytics workflow beginning with understanding the business problem, preparing the data, performing exploratory analysis, and communicating findings through visualizations and business insights.

Rather than simply answering assignment questions, this project demonstrates the complete analytical process from raw data to actionable business recommendations.

---

## Business Questions

This analysis seeks to answer several business questions, including:

- Which product category generated the highest revenue in 2021?
- Which states generated the highest sales for men's and women's products?
- Which retailers sold the most units in 2020 and 2021?
- How did product sales change year over year?
- How did retailer performance change between 2020 and 2021?
- What sales trends and growth opportunities can leadership identify?

---

## Analytics Workflow

This project follows a structured data analytics process:

### 1. Define the Business Problem
- Understand the business objectives.
- Identify the questions leadership wants answered.

### 2. Understand the Data
- Review the three source datasets.
- Examine variables, data types, and relationships.
- Perform initial inspection using descriptive statistics.

### 3. Merge the Data
The product, retailer, and sales datasets were merged into a single analytical dataset prior to cleaning. Merging first allowed data quality issues to be identified across the complete dataset rather than within each individual file.

### 4. Inspect and Clean the Data
The merged dataset was evaluated for data quality issues including:

- Incorrect data types
- Missing values
- Invalid records
- Duplicate information
- Inconsistent categorical values
- Erroneous numerical values
- Potential outliers

Cleaning decisions were documented throughout the notebook and included:

- Converting Invoice Date to datetime format
- Removing redundant date columns
- Correcting invalid Price Per Unit values using the product median
- Correcting Sales Method spelling inconsistencies
- Removing invalid retailer records
- Handling missing values
- Validating data using descriptive statistics and outlier analysis

### 5. Perform Exploratory Data Analysis (EDA)

Business analysis included:

- Product revenue
- Retailer performance
- State sales analysis
- Sales method analysis
- Year-over-year product growth
- Year-over-year retailer growth
- Retailer product mix
- Executive-level business insights

### 6. Communicate Results

Results were communicated through:

- Summary statistics
- Pivot tables
- Business insights
- Presentation-quality visualizations
- Executive recommendations

---

## Dataset

The project uses three datasets:

- TABLE_PRODUCTS_885.csv
- TABLE_RETAILER_885.csv
- TABLE_SALES_885.csv

These datasets were merged into a single analytical dataset for analysis.

---

## Key Findings

The analysis identified several important business insights:

- Men's Street Footwear generated the highest revenue in 2021.
- Every product category experienced significant year-over-year revenue growth.
- Sports Direct and West Gear experienced the largest retailer revenue increases.
- Amazon was the only existing retailer to experience declining revenue.
- Foot Locker and Walmart first appeared in the 2021 data, contributing to overall company growth.
- Product growth occurred across every major product category, suggesting broad market expansion rather than isolated product success.

---

## Visualizations

The project includes executive-level visualizations such as:

- Revenue by Product Category (2021)
- Product Revenue Growth (2020–2021)
- Retailer Revenue Growth
- Retailer Revenue Comparison (2020 vs. 2021)
- Top States for Women's Product Revenue
- Retailer Product Mix
- Additional summary tables and pivot tables

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab
- GitHub

---

## Repository Contents

```
rush_sales_analysis.ipynb
README.md
TABLE_PRODUCTS_885.csv
TABLE_RETAILER_885.csv
TABLE_SALES_885.csv
```

---

## How to Run the Project

1. Open `rush_sales_analysis.ipynb` in Google Colab.
2. Run the notebook from top to bottom.
3. The notebook reads the CSV files directly from the GitHub repository.
4. Review the visualizations and business insights.

---

## Author

**Cory Suhr**

Data Analytics Final Project (GB885)

University of Wisconsin- Madison
