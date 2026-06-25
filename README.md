# Financial Forecasting Frontier: Distributed Machine Learning

## Overview

Financial Forecasting Frontier is an end-to-end banking analytics project that demonstrates the use of Distributed Computing and Machine Learning for analyzing customer behavior, campaign performance, and term deposit subscription trends. The project combines Hadoop, Hive, Apache Spark, Spark ML, Spark Streaming, and Power BI to simulate a modern banking analytics workflow.

---

## Project Objective

* Analyze banking customer data at scale using distributed computing.
* Perform exploratory data analysis using Apache Spark.
* Build predictive machine learning models for term deposit subscription prediction.
* Simulate real-time transaction analysis using Spark Streaming.
* Create an interactive Power BI dashboard for business decision-making.

---

## My Approach

1. Loaded and explored banking data using Spark.
2. Performed large-scale data processing and exploratory analysis.
3. Built and evaluated machine learning models using Spark ML.
4. Implemented distributed data processing and parallel computing concepts.
5. Simulated real-time analytics using Spark Structured Streaming.
6. Developed a multi-page Power BI dashboard to present business insights.

---

## Technologies Used

* Python
* Apache Hadoop
* Apache Hive
* Apache Spark
* PySpark
* Spark MLlib
* Spark Structured Streaming
* Google Colab
* Power BI
* DAX

---

## Dataset Information

**Dataset:** Bank Marketing Dataset

**Records:** 4,521

**Features:** 17

**Target Variable:** `y` (Term Deposit Subscription)

The dataset contains customer demographics, financial information, campaign details, and subscription outcomes.

---

## Notebook Descriptions

### 01_Hadoop_Hive.ipynb

Data ingestion, querying, aggregation, and banking analytics using distributed data management concepts.

### 02_Spark_EDA.ipynb

Exploratory Data Analysis, data transformations, trend discovery, and visualization using Spark.

### 03_Spark_ML.ipynb

Machine learning pipeline development, model training, evaluation, and hyperparameter tuning.

### 04_Data_Parallelism.ipynb

Implementation of Spark data parallelism techniques to improve processing efficiency.

### 05_Spark_Streaming.ipynb

Simulation of real-time transaction processing using Spark Structured Streaming.

---

## Power BI Dashboard

### Dashboard Pages

* Executive Overview
* Customer Segmentation
* Campaign Performance

### Features

* KPI Monitoring
* Customer Profiling
* Campaign Analysis
* Subscription Trends
* Interactive Filters
* Advanced DAX Measures

---

## Outcomes

* Built a complete distributed analytics pipeline.
* Successfully analyzed customer and campaign behavior.
* Developed predictive models for subscription forecasting.
* Demonstrated distributed processing and real-time analytics capabilities.
* Created an interactive business intelligence dashboard.

---

## Model Performance

### Logistic Regression

* Accuracy: 89.17%
* Precision: 87.07%
* Recall: 89.17%
* F1 Score: 87.07%

### Random Forest

* Accuracy: 88.71%
* Precision: 89.99%
* Recall: 88.71%
* F1 Score: 83.93%

### Hyperparameter Tuned Logistic Regression

* Accuracy: 89.06%
* Precision: 86.82%
* Recall: 89.06%
* F1 Score: 86.32%

---

## Key Findings

* Previous campaign outcome was the strongest predictor of subscription.
* Customers with tertiary education maintained higher average balances.
* Retired customers had the highest average account balances.
* Call duration showed a strong relationship with subscription success.
* Contact method and campaign history significantly influenced outcomes.

---

## Business Impact

* Supports targeted marketing strategies.
* Helps identify high-value customer segments.
* Improves campaign effectiveness through data-driven insights.
* Demonstrates scalable analytics for banking environments.
* Provides actionable insights for customer retention and product marketing.

---

## Learnings

* Distributed Computing with Hadoop, Hive, and Spark.
* Large-scale data processing and optimization.
* Machine Learning using Spark MLlib.
* Real-time analytics using Spark Streaming.
* Dashboard development and storytelling using Power BI.
* Data modeling and DAX implementation.

---

## Installation & Setup

### Clone Repository

```bash
git clone <repository-url>
```

### Install Dependencies

```bash
pip install pyspark pandas numpy matplotlib seaborn scikit-learn
```

### Run Notebooks

Open the notebooks in Google Colab or Jupyter Notebook and execute the cells sequentially.

---

## Conclusion

This project demonstrates how distributed computing, machine learning, real-time analytics, and business intelligence can be integrated to solve practical banking analytics problems. The solution provides scalable data processing capabilities while delivering meaningful business insights through predictive modeling and interactive dashboards.

---

## Author

**Akshad Goyanka**

M.Sc. Computer Science (AI & ML)

Data Analytics | Machine Learning | Business Intelligence
