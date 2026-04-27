![Python](https://img.shields.io/badge/Python-3.x-blue)
![Apache Spark](https://img.shields.io/badge/Apache%20Spark-3.5-orange)
![Platform](https://img.shields.io/badge/Platform-Google%20Colab-yellow)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

📊 Distributed Data Processing using Apache Spark (Google Colab)
🚀 Project Overview

This project demonstrates a distributed data processing system using Apache Spark implemented in Google Colab.

It focuses on building an ETL pipeline, performing data analysis with Spark SQL, and comparing performance with pure Python execution.

🎯 Objectives
Implement distributed data processing using Spark
Build a complete ETL (Extract, Transform, Load) pipeline
Perform analysis using Spark SQL
Compare Spark vs Python performance
Visualize results using graphs
⚙️ Technologies Used
Python 🐍
PySpark
Apache Spark
Google Colab
Matplotlib 📊
📂 Project Structure
├── data_generation.py
├── etl_pipeline.py
├── spark_sql_analysis.py
├── performance_comparison.py
├── cleaned_output/
├── report/
└── README.md

🔄 Workflow

1️⃣ Data Generation

Created synthetic dataset (1000 records)
Included missing values (NULLs)
Simulated real-world sales data

2️⃣ ETL Pipeline (Spark Transformations)

Data cleaning (removed NULL values)
Removed duplicates
Created new columns:
total_price
discount
final_price
Applied transformations:
filter()
groupBy()
reduce()

3️⃣ Data Analysis (Spark SQL)

Converted DataFrame → SQL Table
Executed queries:
Total revenue
Category-wise sales
Product-wise sales
Top transactions

4️⃣ Performance Comparison

Implemented same logic in:
Pure Python
Spark (RDD)
Measured execution time


📊 Result:


Python faster for small data
Spark scalable for large datasets

📈 Visualization

Bar chart comparing execution time:
Python vs Spark
Implemented using Matplotlib

📊 Sample Results

Metric	Value
Total Revenue	2.6M+
Top Product	Phone
Best Category	Electronics
## 📸 Screenshots

### 🔹 Spark Setup
![Spark Setup](https://github.com/amnnajaved-dev1/parallel-and-distributed-sys/raw/main/Spark%20setup.png)

### 🔹 Performance Graph
![Graph](https://github.com/amnnajaved-dev1/parallel-and-distributed-sys/raw/main/Graph%20(VERY%20IMPORTANT).png)

### 🔹 ETL Transformation
![ETL](https://github.com/amnnajaved-dev1/parallel-and-distributed-sys/raw/main/ETL%20transformation.png)

### 🔹 DataFrame Output
https://github.com/amnajaved-dev1/parallel-and-distributed-sys/blob/main/DataFrame%20output.png
