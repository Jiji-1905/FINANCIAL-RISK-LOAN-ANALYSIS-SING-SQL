# 💰 Financial Risk & Loan Analysis using SQL

![SQL Server](https://img.shields.io/badge/SQL%20Server-Microsoft-blue?logo=microsoftsqlserver)
![Data Warehouse](https://img.shields.io/badge/Data%20Warehouse-Star%20Schema-orange)
![Domain](https://img.shields.io/badge/Domain-Finance%20Analytics-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Level](https://img.shields.io/badge/Level-Advanced-purple)

---

## 🧠 Project Overview

This project focuses on analyzing **loan data** to identify **financial risk patterns** and support data-driven lending decisions.

A **Data Warehouse (Star Schema)** was designed using SQL to transform raw loan data into a structured analytical model for efficient querying and reporting.

---

## 🎯 Objectives

* Identify **high-risk loan applicants**
* Analyze **loan default patterns**
* Segment customers based on **income and credit history**
* Enable **data-driven financial decision-making**

---

## 🏗️ Data Architecture

```
RAW DATA (LOAN_DATA)
        ↓
Data Cleaning & Transformation
        ↓
Dimension Tables (DIM_CUSTOMER, DIM_PROPERTY, DIM_CREDIT)
        ↓
Fact Table (FACT_LOAN)
        ↓
Risk Analysis & Insights
```

---

## ⭐ Data Model (Star Schema)

### 🔹 Fact Table: FACT_LOAN

* Loan_ID
* Customer_Key
* Property_Key
* Credit_Key
* ApplicantIncome
* CoapplicantIncome
* LoanAmount
* Loan_Amount_Term
* Loan_Status

### 🔹 Dimension Tables

#### 👤 DIM_CUSTOMER

* Customer_Key (PK)
* Gender
* Married
* Dependents
* Education
* Self_Employed

#### 🏠 DIM_PROPERTY

* Property_Key (PK)
* Property_Area

#### 📊 DIM_CREDIT

* Credit_Key (PK)
* Credit_History

---

## ⚙️ Key Features

* Data Cleaning using `COALESCE()` and transformations
* Surrogate Keys using `ROW_NUMBER()`
* Implementation of **Star Schema Data Warehouse**
* Primary & Foreign Key constraints for data integrity
* Financial Risk Analysis using SQL

---

## 💻 SQL Techniques Used

* Joins (INNER JOIN)
* Aggregations (`SUM`, `COUNT`)
* Window Functions (`OVER`)
* CASE Statements (Segmentation)
* Common Table Expressions (CTEs)
* Indexing & Constraints

---

## 📊 Analysis Performed

### 🔥 Default Rate Analysis

Calculated percentage of approved vs rejected loans

### 📊 Credit Risk Analysis

Evaluated impact of credit history on loan approval

### 💰 Income Segmentation

Classified customers into Low, Medium, High income groups

### 🏠 Property Risk Analysis

Analyzed loan distribution and risk by property area

### ⚠️ High-Risk Customer Profiling

Identified customer segments with highest default rates

---

## 📈 Key Insights

* Customers with **no credit history** have significantly higher default rates
* **Low-income applicants** show higher loan rejection probability
* Property location influences **financial risk exposure**
* Self-employed individuals show **higher variability in repayment**

---

## 🧠 Skills Demonstrated

* Advanced SQL
* Data Warehousing (Star Schema)
* Financial Risk Analysis
* Data Cleaning & Transformation
* Business Insight Generation

---

## 🏆 Project Outcome

* Built a complete **financial analytics solution using SQL**
* Enabled identification of **high-risk loan segments**
* Demonstrated real-world **banking analytics use case**

---

## 🚀 Future Improvements

* Build interactive dashboard using Power BI
* Integrate Machine Learning for predictive risk modeling
* Automate ETL pipeline

---

## 👨‍💻 Author

**JIJI BABU**

---

