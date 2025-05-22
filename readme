# 🩺 Project Gladiator - Healthcare Case Study (COVID-19 Data Analysis)

## 📊 Overview

This project focuses on analyzing COVID-19 datasets using Big Data tools and frameworks. Our aim is to design a scalable data pipeline and apply data engineering and visualization techniques to extract meaningful insights from COVID-19 case data for April, May, and June 2022.


## 📂 Project Structure

### 1. Problem Statement
COVID-19 triggered a global healthcare crisis. This project uses Big Data tools to manage and visualize COVID-19 trends to improve data-driven decision-making in healthcare.

### 2. Data Ingestion
- **Sources**: GitHub COVID-19 dataset (April, May, June 2022)
- **Tools**:
  - Local Storage (April)
  - HDFS + Hive (May)
  - MySQL (June)
- **Final step**: All datasets loaded into PySpark DataFrames

### 3. Data Cleansing
- Dropped null and duplicate values
- Standardized missing values
- Combined all monthly data into a unified DataFrame

### 4. Transformations Using PySpark
- Filtering and grouping by country
- Top/Least affected countries by confirmed cases, deaths, and incident rate
- Column renaming, sorting, and datetime handling

### 5. Optimization
- Applied various storage formats and compression techniques:
  - GZIP
  - Snappy
  - ORC
  - BZIP2
- Implemented partitioning and bucketing
- Created and managed Delta Tables

### 6. Spark Streaming Using Kafka
- Kafka producer sends streaming COVID-19 data
- PySpark reads and processes streaming data
- Stores results in HDFS and displays in console

### 7. Spark Integration with AWS S3
- Configured AWS S3 access via Spark and Hadoop
- Uploaded processed data to an S3 bucket
- Required `.jar` libraries and configuration files updated

### 8. Data Visualization using Tableau
- Visualized COVID-19 trends:
  - Confirmed cases
  - Death rates
  - Country-wise insights
- Created dynamic and interactive dashboards for stakeholders

---

## 🛠️ Tools & Technologies

- Apache Spark
- Apache Kafka
- Apache Hive
- MySQL
- Hadoop HDFS
- AWS S3
- Tableau
- Shell Scripting
- PySpark
- Git

---

## 🧠 Key Learnings

- Building a hybrid data ingestion pipeline (batch + streaming)
- Cleansing large datasets using Spark
- Optimizing data storage formats for performance
- Real-time data processing with Kafka and Spark Streaming
- Cloud integration with AWS S3
- Visual storytelling with Tableau

---

## 📎 How to Run

1. Clone this repository.
2. Follow `data_ingestion.sh` and `mysql_loader.sh` to prepare data.
3. Start services: HDFS, Hive, MySQL, Kafka, Zookeeper.
4. Run Spark jobs (`transform.py`, `streaming_consumer.py`).
5. Visualize output with Tableau.

---

## 📦 Dataset

- Source: [Johns Hopkins COVID-19 Data](https://github.com/CSSEGISandData/COVID-19)
- Scope: April, May, June 2022

---

## 📈 Sample Visualizations

- Top 10 countries by confirmed cases
- Global incident rate distribution
- Daily new cases trend line
- Recovery vs. fatality comparison

---

## 🔒 Credentials

> **Note:** All access keys shown in this report have been revoked and are placeholders. Please use your own AWS keys.

---

## 📬 Contact

For any queries or feedback, reach out to the team via issues or pull requests.

---

