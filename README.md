# Ecommerce Data ETL Pipeline

A beginner-friendly ETL (Extract, Transform, Load) project that simulates a real-world data engineering workflow using an Ecommerce Customers dataset.  
Built entirely in Google Colab using Python (Pandas) and simulated Airflow DAGs for automation.

---

## 🛠 Tech Stack
- Python 3
- Pandas
- Google Colab (for development)
- (Optional) Apache Airflow (for future automation)

---

## 📋 Project Overview

In this project, we created a simple ETL pipeline:
- **Extract**: Load raw ecommerce customer data from a CSV file.
- **Transform**: Clean the data (drop nulls, correct types).
- **Load**: Save the cleaned data into a new CSV file (`cleaned_data.csv`).

We also simulated ETL tasks using Airflow concepts like DAGs and task dependencies (manually, inside the notebook).

---

## 📈 ETL Steps

### 1. Extract
- Read the raw data file `Ecommerce Customers.csv` using Pandas.
- Displayed first few records to validate extraction.

### 2. Transform
- Removed rows with missing critical values.
- Converted data types if necessary.
- Basic cleaning to ensure quality.

### 3. Load
- Saved the cleaned data into a new file `cleaned_data.csv`.
- Verified number of records after cleaning.

---

## 🚀 How to Run

1. Upload your `Ecommerce Customers.csv` to Colab.
2. Run the notebook cells one by one.
3. Cleaned data will be saved as `cleaned_data.csv`.
4. (Optional) Extend the project by using real Apache Airflow locally for full automation.

---

## 🧠 Learning Outcome

- Understanding of basic ETL process.
- Hands-on experience with data extraction, cleaning, and loading.
- Introduction to Airflow DAGs and task orchestration (conceptual).

---


