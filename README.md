# loan_approval_analysis_powerbi
Power BI dashboard analyzing loan approval patterns using demographic and financial data.
# Loan Approval Analysis Dashboard

## 📊 Project Overview

This project presents an interactive **Power BI dashboard** that analyzes loan approval patterns based on applicant demographics, financial information, and credit history.
The objective of the project is to identify key factors that influence whether a loan application is approved or rejected.

---

## 📁 Dataset Description

The dataset contains information about loan applicants and their loan status. Key columns include:

* **Gender** – Applicant gender
* **Married** – Marital status
* **Dependents** – Number of dependents
* **Education** – Graduate / Not Graduate
* **Self Employed** – Employment status
* **ApplicantIncome** – Applicant monthly income
* **CoapplicantIncome** – Co-applicant income
* **LoanAmount** – Loan amount requested
* **Loan_Amount_Term** – Loan repayment term
* **Credit_History** – Credit history (1 = good and good repyment history, 0 = bad or fresh applicant)
* **Property_Area** – Urban / Semiurban / Rural
* **Loan_Status** – Loan Approved (Y) or Rejected (N)

---

## 🧹 Data Cleaning & Transformation

Data preprocessing was performed in **Power Query** before building the dashboard.

Steps performed:
* Identified some **null** values and removed them.
* Identified **missing values/blanks** in the dataset
* Replaced missing values using statistical techniques:

  * **Categorical columns** → replaced with **Mode (most frequent value)**
  * **Numeric columns** → replaced with **Median** to reduce the effect of outliers
* Corrected **data types**
* Removed inconsistencies and prepared the dataset for analysis

---

## 📐 Data Analysis & Measures

Several **DAX measures** were created to calculate key metrics used in the dashboard.

Key metrics include:

* **Total Loan Applications**
* **Approved Loans**
* **Rejected Loans**
* **Loan Approval Rate**

Example calculation:

Approval Rate = Approved Loans / Total Applications

---

## 📊 Dashboard Features

The Power BI dashboard provides insights through multiple visualizations:

* **KPI Cards**

  * Total Applications
  * Approved Loans
  * Rejected Loans
  * Approval Rate

* **Loan Approval by Education**

* **Credit History Impact on Loan Approval**

* **Income vs Loan Amount Scatter Plot**

* **Loan Approval by Property Area**

* **Applicant Demographic Analysis**

---

## 🔍 Key Insights

Some insights derived from the dashboard include:

* Applicants with **good credit history** have a much higher chance of loan approval.
* **Semiurban property areas** show a higher number of approved loans.
* There is a visible relationship between **applicant income and loan amount requested**.
* Education and employment status also influence approval trends.

---

## 🖼 Dashboard Preview

![Loan Approval Dashboard](loan dashboard.png.png)

---

## 🛠 Tools & Technologies Used

* **Power BI**
* **Power Query**
* **DAX**
* **Data Visualization**

---

## 🎯 Project Objective

This project demonstrates skills in:

* Data cleaning and preprocessing
* Power BI dashboard development
* Data visualization
* Data-driven insight generation
* DAX calculations

