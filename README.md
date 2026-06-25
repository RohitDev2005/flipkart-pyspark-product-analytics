# Flipkart Product Analytics using PySpark and Databricks

## Overview

This project focuses on analyzing Flipkart product data using PySpark in Databricks. The objective was to understand how PySpark can be used to process large datasets, perform data cleaning, transform raw data into a structured format, and generate useful business insights.

The dataset contains information about products listed on Flipkart, including product details, ratings, reviews, pricing, categories, and fulfillment status. By processing this data with Spark DataFrames, the project demonstrates a simple data engineering and analytics workflow.

---

## Objectives

* Load and process product data using PySpark.
* Perform data quality checks by identifying missing and duplicate records.
* Clean and transform the dataset for analysis.
* Create additional features to improve analysis.
* Analyze product categories, ratings, reviews, and fulfillment details.
* Generate business insights from the processed data.

---

## Technologies Used

* Python
* PySpark
* Databricks

---

## Dataset

The dataset contains more than 5,000 Flipkart product records with the following information:

* Product ID
* Product Title
* Product Category
* Platform
* Product Rating
* Number of Ratings
* Number of Reviews
* Product Price
* Star Rating Distribution
* Fulfillment Status

---

## Project Workflow

### 1. Data Ingestion

The dataset was uploaded into Databricks and loaded as a Spark DataFrame for distributed data processing.

### 2. Data Exploration

Before performing any transformations, the dataset was explored by examining its schema, checking record counts, and reviewing descriptive statistics.

### 3. Data Cleaning

Data quality checks were performed to identify missing values and duplicate records. Column names were standardized to improve readability, duplicate records were removed, and missing values were handled appropriately.

### 4. Feature Engineering

Additional columns such as **Popularity Score** and **Review-to-Rating Ratio** were created to provide more meaningful insights during analysis.

### 5. Business Analysis

Several analytical queries were performed to understand:

* Product category distribution
* Average ratings across categories
* Most reviewed products
* Most popular products
* Platform-wise product distribution
* Fulfillment analysis
* Rating distribution

---

## Key Learnings

Through this project, I gained practical experience with:

* Working with Spark DataFrames
* Data cleaning and transformation using PySpark
* Feature engineering
* Aggregations using `groupBy()`
* Data analysis using distributed processing in Databricks

---

## Repository Structure

```text
flipkart-pyspark-product-analytics/
│
├── notebook/
│   └── Flipkart_Analysis.ipynb
│
├── data/
│   └── Flipkart.csv
│
├── screenshots/
│
├── README.md
```
## 🌟 About Me

Hi! I’m a Computer Engineering student with a strong interest in **Data Analytics and Data Engineering**.  
I enjoy working with SQL, data modeling, and building end-to-end data pipelines.  

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge\&logo=linkedin\&logoColor=white)](https://www.linkedin.com/in/rohit-devshatwar-178249296)  
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge\&logo=leetcode\&logoColor=black)](https://leetcode.com/u/Rohit_Devshatwar/)  
[![GeeksforGeeks](https://img.shields.io/badge/GeeksforGeeks-2F8D46?style=for-the-badge\&logo=geeksforgeeks\&logoColor=white)](https://www.geeksforgeeks.org/profile/devshatwxqs5)
