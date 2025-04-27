# Assignment Overview

In this assignment, I explored basic examples of using **Apache Spark** on **Databricks**. I worked with **DataFrames** for data manipulation, used **Spark SQL** to run queries on structured data, and also implemented a simple **word count** program using **RDDs**. The goal was to get familiar with Spark’s main APIs and understand how big data is processed efficiently.

# Instructions to Run the Code

- **Platform:** Databricks (Cloud environment)
- **Spark Version:** 3.5.0 (Databricks Runtime)
- **Language:** Python 3 (PySpark)
- **Dependencies:**  
  No external libraries were needed outside of what Databricks provides by default (PySpark is already included).

**Steps to run:**
1. Open the Databricks notebook.
2. Attach the notebook to a running cluster.
3. Run the cells sequentially.

# Explanation of Each Example

- **Creating a DataFrame:**  
  Created a small DataFrame manually to practice loading and displaying structured data.

- **Basic DataFrame Operations:**  
  Selected specific columns, applied filters to rows, and grouped data to perform simple aggregations.

- **Spark SQL:**  
  Registered a DataFrame as a temporary view and used SQL queries like `SELECT`, `WHERE`, and `ORDER BY` to retrieve and filter data.

- **Word Count using RDDs:**  
  Loaded a text file into an RDD, split lines into words, mapped each word to a pair (word, 1), and then reduced it by key to count word occurrences.

Each example demonstrates different ways to work with data in Spark — from high-level APIs like DataFrames and SQL to lower-level operations with RDDs.
