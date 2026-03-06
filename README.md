# loan_approval_analysis_powerbi
Power BI dashboard analyzing loan approval patterns using demographic and financial data.
# Loan Approval Analysis Dashboard (Power BI)

## 📊 Project Overview

This project analyzes loan approval patterns using a Power BI dashboard.
The goal is to understand the key factors that influence whether a loan application gets approved or rejected.

The dashboard provides insights into applicant demographics, income distribution, credit history, and property areas to identify trends affecting loan approvals.

---

## 📁 Dataset

The dataset contains information about loan applicants including:

* Gender
* Marital Status
* Dependents
* Education
* Self Employment
* Applicant Income
* Loan Amount
* Credit History
* Property Area
* Loan Status (Approved / Rejected)

---

## 🧹 Data Cleaning & Transformation

Data preprocessing was performed using **Power Query**.

Missing values were handled using statistical imputation techniques:

* **Categorical columns** (Gender, Married, Dependents, etc.)

  * Replaced missing values with the **Mode (most frequent value)**.

* **Numeric columns** (Loan Amount, Applicant Income)

  * Replaced missing values with the **Median** to reduce the influence of outliers.

Additional transformations included:

* Data type corrections
* Removing inconsistencies
* Preparing data for analysis

---

## 📐 Data Modeling & Measures

DAX measures were created to calculate key metrics:

* **Total Applications**
* **Approved Loans**
* **Rejected Loans**
* **Loan Approval Rate**

Example KPI:

Approval Rate = Approved Loans / Total Applications

---

## 📈 Dashboard Features

The dashboard includes:

* KPI cards showing total applications and approval rate
* Loan approval distribution by **education level**
* Analysis of **credit history impact on loan approval**
* Scatter plot showing relationship between **income and loan amount**
* Approval analysis by **property area**
* Demographic insights of loan applicants

---

## 🔍 Key Insights

* Loan applicants with **credit history = 1** have a significantly higher approval rate.
* **Semiurban property areas** show higher loan approval counts.
* Applicants with **higher incomes tend to request larger loan amounts**.
* Credit history plays a **major role in loan approval decisions**.

---

## 🖼 Dashboard Preview

![Dashboard](dashboard.png)

---

## 🛠 Tools Used

* **Power BI**
* **Power Query**
* **DAX**
* **Data Visualization**
* **Data Cleaning**

---

## 📌 Project Purpose

This project demonstrates skills in:

* Data cleaning and preprocessing
* Power BI dashboard development
* Data visualization
* Business insight generation
* DAX calculations

---

## 🚀 Future Improvements

* Add interactive slicers for deeper exploration
* Perform additional statistical analysis
* Include predictive modeling for loan approval
