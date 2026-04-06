# 💰 Financial Risk & Loan Analysis using SQL

![SQL Server](https://img.shields.io/badge/SQL%20Server-Microsoft-blue?logo=microsoftsqlserver)
![Data Warehouse](https://img.shields.io/badge/Data%20Warehouse-Star%20Schema-orange)
![Domain](https://img.shields.io/badge/Domain-Finance%20Analytics-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Level](https://img.shields.io/badge/Level-Advanced-purple)

---

## 🧠 Project Overview

This project focuses on analyzing **loan data** to identify financial risk patterns and support data-driven lending decisions.

A **Star Schema Data Warehouse** was built using SQL to transform raw loan data into a structured format for analysis.

---

## 🎯 Objectives

- Identify high-risk loan applicants  
- Analyze loan approval and rejection patterns  
- Segment customers based on income and credit history  
- Support financial decision-making using data  

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
- Loan_ID  
- Customer_Key  
- Property_Key  
- Credit_Key  
- ApplicantIncome  
- CoapplicantIncome  
- LoanAmount  
- Loan_Amount_Term  
- Loan_Status  

### 🔹 Dimension Tables

#### 👤 DIM_CUSTOMER
- Customer_Key (Primary Key)  
- Gender  
- Married  
- Dependents  
- Education  
- Self_Employed  

#### 🏠 DIM_PROPERTY
- Property_Key (Primary Key)  
- Property_Area  

#### 📊 DIM_CREDIT
- Credit_Key (Primary Key)  
- Credit_History  

---

## ⚙️ Key Features

- Data Cleaning using SQL functions  
- Surrogate Keys using ROW_NUMBER()  
- Star Schema Data Modeling  
- Primary & Foreign Key Constraints  
- Financial Risk Analysis  

---

## 💻 SQL Techniques Used

- INNER JOIN  
- SUM, COUNT (Aggregations)  
- CASE Statements  
- Window Functions (OVER)  
- CTE (Common Table Expressions)  
- Indexing & Constraints  

---

## 📊 Analysis Performed

### 🔥 Default Rate Analysis
Calculated percentage of loan approvals vs rejections  

### 📊 Credit Risk Analysis
Analyzed impact of credit history on loan approval  

### 💰 Income Segmentation
Grouped applicants into Low, Medium, High income  

### 🏠 Property Risk Analysis
Evaluated risk across different property areas  

### ⚠️ High-Risk Customer Profiling
Identified customer segments with highest defaults  

---

## 📈 Key Insights

- Customers with no credit history have higher default rates  
- Low-income applicants show higher rejection probability  
- Property location impacts financial risk  
- Self-employed individuals show higher repayment variability  

---

## 🧠 Skills Demonstrated

- Advanced SQL  
- Data Warehousing  
- Financial Risk Analysis  
- Data Cleaning & Transformation  
- Business Insights  

---

## 🏆 Project Outcome

Built a complete financial analytics solution using SQL and identified high-risk loan segments.

---

## 🚀 Future Improvements

- Build Power BI dashboard  
- Add machine learning model  
- Automate ETL pipeline  

---

## 👨‍💻 Author

**JIJI BABU**

---


If you like this project, give it a ⭐ on GitHub!
