# Financial Forecasting Frontier: Distributed Machine Learning

## Overview

Financial Forecasting Frontier is a Distributed Machine Learning capstone project focused on applying large-scale data processing, machine learning, and real-time analytics techniques to banking data. The project demonstrates the use of Hadoop, Hive, Apache Spark, Spark MLlib, Structured Streaming, and Data Parallelism to extract insights, build predictive models, and simulate real-time decision-making systems.

The project uses the Bank Marketing Dataset to analyze customer behavior and predict term deposit subscriptions while showcasing distributed computing concepts used in modern financial institutions.

---

## Project Objectives

* Perform distributed data analysis using Hadoop, Hive, and Apache Spark.
* Explore and preprocess banking customer data.
* Build and evaluate machine learning models using Spark MLlib.
* Demonstrate data parallelism for scalable analytics.
* Simulate real-time analytics using Spark Structured Streaming.
* Generate actionable business insights from banking data.
* Understand resource utilization, distributed execution, and scheduling concepts.

---

## Technologies Used

### Distributed Computing

* Apache Hadoop
* Apache Hive
* Apache Spark
* Spark SQL
* Spark Structured Streaming

### Machine Learning

* Spark MLlib
* Logistic Regression
* Random Forest Classification
* Hyperparameter Tuning
* Cross Validation

### Programming & Analytics

* Python
* Pandas
* NumPy
* Matplotlib

### Development Environment

* Google Colab
* GitHub

---

## Dataset Information

### Dataset

Bank Marketing Dataset Provided by Alma Better

### Domain

Banking and Financial Services

### Target Variable

`y`

* Yes → Customer subscribed to a term deposit
* No → Customer did not subscribe

### Features Include

* Age
* Job
* Marital Status
* Education
* Account Balance
* Housing Loan Status
* Personal Loan Status
* Campaign Information
* Contact Information
* Previous Campaign Outcomes

---

## Project Structure

```text
Financial-Forecasting-Frontier-Distributed-ML
│
├── 01_Hadoop_Hive.ipynb
├── 02_Spark_EDA.ipynb
├── 03_Spark_ML.ipynb
├── 04_Data_Parallelism.ipynb
├── 05_Spark_Streaming.ipynb
│
├── bank.csv
│
└── README.md
```

---

## Notebook Descriptions

### 01_Hadoop_Hive.ipynb

Topics Covered:

* Banking data analysis
* Hive-style querying
* Aggregations
* Correlation analysis
* Customer segmentation
* Banking business insights

---

### 02_Spark_EDA.ipynb

Topics Covered:

* Data loading and inspection
* Data filtering
* Aggregations
* User Defined Functions (UDFs)
* Spark SQL queries
* Data visualization
* Exploratory Data Analysis

---

### 03_Spark_ML.ipynb

Topics Covered:

* Data preprocessing
* Feature engineering
* Logistic Regression
* Random Forest
* Model evaluation
* Hyperparameter tuning
* Feature coefficient analysis

Key Results:

* Logistic Regression Accuracy: ~89%
* F1 Score: ~87%

---

### 04_Data_Parallelism.ipynb

Topics Covered:

* Data partitioning
* Parallel aggregations
* Distributed machine learning
* Resource monitoring
* Spark scheduling
* DAG execution concepts

Key Results:

* 4 Spark partitions used
* Distributed model training
* Efficient CPU and memory utilization

---

### 05_Spark_Streaming.ipynb

Topics Covered:

* Structured Streaming
* Real-time aggregations
* Real-time predictions
* Window operations
* Watermarking
* Trend analysis

Key Results:

* Simulated streaming analytics
* Real-time prediction workflow
* Window-based monitoring
* Watermark handling demonstration

---

## Installation and Setup

### Clone Repository

```bash
git clone https://github.com/Aks18had/Financial-Forecasting-Frontier-Distributed-ML.git
cd Financial-Forecasting-Frontier-Distributed-ML
```

### Install Dependencies

```bash
pip install pyspark pandas numpy matplotlib
```

---

## Running the Project

### Google Colab Setup

Mount Google Drive:

```python
from google.colab import drive
drive.mount('/content/drive')
```

Install PySpark:

```python
!pip install pyspark -q
```

Update Dataset Path:

```python
DATA_PATH = "/content/drive/MyDrive/Distributed_ML_Project/bank.csv"
```

Run notebooks sequentially.

---

## Recommended Execution Order

1. 01_Hadoop_Hive.ipynb
2. 02_Spark_EDA.ipynb
3. 03_Spark_ML.ipynb
4. 04_Data_Parallelism.ipynb
5. 05_Spark_Streaming.ipynb

---

## Key Findings

* Previous campaign outcomes strongly influence subscription behavior.
* Customers with housing loans show higher subscription likelihood.
* Customers with personal loans show lower subscription likelihood.
* Logistic Regression achieved the best overall model performance.
* Data parallelism significantly improves processing efficiency.
* Structured Streaming enables continuous real-time analytics.
* Windowing and watermarking support reliable stream processing.

---

## Business Impact

This project demonstrates how distributed machine learning can help financial institutions:

* Improve customer targeting.
* Increase marketing campaign effectiveness.
* Support real-time decision making.
* Scale analytics pipelines.
* Monitor customer behavior continuously.
* Generate actionable business intelligence.

---

## Learning Outcomes

Through this project, the following concepts were applied:

* Distributed Computing
* Hadoop and Hive Analytics
* Apache Spark Processing
* Data Parallelism
* Spark ML Pipelines
* Model Evaluation
* Hyperparameter Optimization
* Structured Streaming
* Window Operations
* Watermarking
* Real-Time Analytics

---

## Repository

GitHub Repository:

https://github.com/Aks18had/Financial-Forecasting-Frontier-Distributed-ML

---

## Author

**Akshad Goyanka**

MSc Computer Science (Artificial Intelligence & Machine Learning)

Woolf University
