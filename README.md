# 🏦 Bank Loan Analysis

A data analytics project that provides insights into loan applications, disbursements, repayments, and borrower profiles using **SQL** and **Power BI**.  
This project demonstrates an end-to-end pipeline for solving real-world business problems by combining **data querying, data modeling, and interactive dashboarding**.

---

## 📌 Problem Statement

The objective of this project is to help a bank monitor and analyze its loan portfolio effectively.  

### **Dashboard 1: Summary**
- **Key Metrics (KPIs):**
  - Total Loan Applications (with MTD and MoM trends)
  - Total Funded Amount (with MTD and MoM trends)
  - Total Amount Received (with MTD and MoM trends)
  - Average Interest Rate (with MTD and MoM changes)
  - Average Debt-to-Income (DTI) Ratio (with MTD and MoM changes)
- **Good Loan vs Bad Loan KPIs:**
  - Good Loan % / Applications / Funded Amount / Received Amount
  - Bad Loan % / Applications / Funded Amount / Received Amount
- **Loan Status Grid View** for detailed breakdown of portfolio health.

### **Dashboard 2: Overview**
- **Monthly Trends** (applications, funded, received amounts by issue date)
- **Regional Analysis** (loan distribution by state)
- **Loan Term Analysis** (short vs long term loans)
- **Employment Length Analysis** (borrower employment history impact)
- **Loan Purpose Breakdown** (why borrowers take loans)
- **Home Ownership Analysis** (impact of ownership status on lending)

### **Dashboard 3: Details**
- A comprehensive **details dashboard** offering borrower-level and loan-level insights in a consolidated view.  
- Enables users to drill down into borrower profiles, repayment behaviors, and loan performance.

---

## ⚙️ Project Workflow

1. **Database & Data Preparation (SQL Server)**
   - Created and loaded loan data into MS SQL Server.
   - Wrote SQL queries to compute KPIs and aggregations.  
   - Performed data cleaning, grouping, and summarization.

2. **SQL Queries for Business Metrics**
   - Loan applications (total, monthly, MTD, PMTD).
   - Loan amounts (funded vs received).
   - Interest rate and DTI calculations.
   - Good Loan vs Bad Loan classification.
   - Regional, term, purpose, and home ownership analysis.  
   *(Queries available in `Query Doc.docx`)*

3. **Data Visualization (Power BI)**
   - Connected Power BI to SQL Server.
   - Built interactive dashboards with KPIs, charts, and slicers.
   - Implemented time intelligence functions (MTD, MoM).
   - Designed intuitive, recruiter-ready visualizations.

---

## 📊 Tools & Technologies
- **SQL Server** (MS SQL Server 19.0 + SSMS)
- **Power BI** (June 2023 version)
- **Excel / MS Office** (for initial exploration)

---

## 🚀 Key Insights
- Month-over-Month loan trends show **seasonal variations** in applications.
- Regional disparities highlight states with **higher lending activity**.
- **Employment length** and **home ownership** strongly influence loan approvals.
- Clear separation between **good loans** (repaid) vs **bad loans** (charged off) helps in **risk management**.


