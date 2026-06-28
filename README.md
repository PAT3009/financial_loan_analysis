# Financial Loan Portfolio Analysis

**End-to-End Data Analysis Project** | SQL + Power BI

## 📋 Project Overview

This project analyzes a bank loan portfolio to evaluate lending performance, borrower characteristics, and loan repayment behavior.

The analysis combines SQL for data extraction and exploratory analysis with Power BI for interactive dashboard development, providing actionable insights into loan performance and portfolio quality.

**Core Business Question:**

*"How is the bank's loan portfolio performing, and what borrower characteristics influence lending activity and repayment outcomes?"*

---

## 🎯 Business Problem

Banks need to continuously monitor loan portfolios to balance business growth with credit risk.

Understanding borrower profiles, loan performance, repayment behavior, and lending trends enables financial institutions to optimize lending strategies, improve portfolio quality, and reduce default risk.

This project focuses on analyzing historical loan data to identify lending patterns, evaluate portfolio health, and support data-driven decision-making.

---

## 📊 Project Scope

### 1. Data Understanding & Preparation

* Data quality assessment
* Missing value and duplicate checks
* Data type validation
* Data preprocessing using SQL

### 2. Exploratory Data Analysis (SQL)

* Loan status distribution
* Grade analysis
* Home ownership analysis
* Employment length analysis
* Interest rate analysis
* Debt-to-Income (DTI) analysis
* Monthly lending trends

### 3. KPI Analysis

* Total Loan Applications
* Total Funded Amount
* Total Amount Received
* Average Interest Rate
* Average DTI
* Good Loan vs Bad Loan Analysis

### 4. Interactive Dashboard Development (Power BI)

* Executive Summary Dashboard
* Portfolio Overview Dashboard
* Loan Details Dashboard

### 5. Business Insights & Recommendations

* Portfolio performance evaluation
* Borrower segmentation
* Lending trend analysis
* Credit risk observations
* Business recommendations

---

## 📁 Dataset Summary

* **Rows:** 38,576
* **Columns:** 24
* **Loan Status:** Current, Fully Paid, Charged Off
* **Missing Values:** Removed during preprocessing
* **Duplicate Records:** Removed during preprocessing

### Key Features

* Loan ID
* Loan Status
* Loan Amount
* Total Payment
* Interest Rate
* DTI
* Grade
* Sub Grade
* Purpose
* Home Ownership
* Employment Length
* Address State
* Issue Date
* Annual Income
* Term

---

## 🛠️ Tools & Technologies

* **SQL Server**
* **Power BI**
* **Excel**
* **Git & GitHub**

---

## 📂 Project Structure

```text
financial_loan_analysis/
│
├── data/
│   └── financial_loan.csv
│
├── sql/
│   ├── 01_data_preprocessing.sql
│   ├── 02_eda.sql
│   └── 03_dashboard_queries.sql
│
├── powerbi/
│   └── financial_loan_dashboard.pbix
│
├── docs/
│   ├── 01_project_overview.pdf
│   ├── 02_data_dictionary.pdf
│   ├── 03_analysis_report.pdf
│   └── 04_key_insights.pdf
│
└── README.md
```

---

## 🚀 How to Use

1. Execute the SQL scripts sequentially:

   * Data Preprocessing
   * Exploratory Data Analysis
   * Dashboard Queries
2. Open the Power BI dashboard (.pbix file).
3. Explore the interactive dashboards using filters such as Grade, State, Purpose, and Good vs Bad Loan.
4. Review the analysis report for detailed findings and business recommendations.

---

## 💡 Key Insights

* The portfolio contains **38.6K** loan applications with over **$435.8M** funded.
* **Good Loans account for over 86%** of total applications, indicating a healthy loan portfolio.
* Loan applications, funded amount, and repayments increased steadily throughout the year, with **December recording the highest lending activity**.
* **Debt Consolidation** is the primary borrowing purpose across all credit grades.
* Borrowers with **10+ years of employment** account for the highest lending volume.
* **Mortgage** and **Rent** borrowers represent nearly the entire customer portfolio.
* California and New York contribute the largest share of loan applications and funding.
* Borrowers with higher interest rates and DTI tend to appear more frequently in the Charged Off segment.

---

## 📊 Dashboard Overview

### Executive Summary

Provides an overview of portfolio KPIs, Good vs Bad Loan performance, and Loan Status analysis.

### Portfolio Overview

Visualizes lending trends by:

* Month
* State
* Loan Term
* Employment Length
* Loan Purpose
* Home Ownership

Interactive filters allow users to analyze different borrower segments.

### Loan Details

Displays transaction-level loan records, enabling users to drill down into individual loans and borrower information.

---

## 💼 Business Recommendations

* Continue prioritizing low-risk borrower segments while maintaining portfolio growth.
* Closely monitor borrowers with higher DTI ratios and elevated interest rates.
* Expand lending strategies in high-performing markets such as California and New York.
* Develop specialized products for Debt Consolidation, as it represents the largest borrowing demand.
* Strengthen monitoring of Charged Off loans to reduce future credit losses.
* Utilize dashboard-driven monitoring for continuous portfolio performance evaluation.

---

## 📸 Dashboard Preview

### Executive Summary Dashboard

*(Insert Summary Dashboard Screenshot)*

### Portfolio Overview Dashboard

*(Insert Overview Dashboard Screenshot)*

### Loan Details Dashboard

*(Insert Details Dashboard Screenshot)*

---

## 📚 References & Acknowledgements

Dataset used for educational and portfolio purposes.

This project demonstrates an end-to-end data analysis workflow using SQL for data preparation and analysis, combined with Power BI for business intelligence and interactive reporting.

---

## 👤 Author

**Trieu Phuong Anh**

**GitHub:** https://github.com/PAT3009

**LinkedIn:** https://www.linkedin.com/in/phuong-anh-trieu-30i9/

**Email:** [phuonganht3009@gmail.com](mailto:phuonganht3009@gmail.com)
