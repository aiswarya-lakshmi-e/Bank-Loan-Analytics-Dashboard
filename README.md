# 🏦 Bank Loan Analytics Dashboard | Power BI

A comprehensive Bank Loan Report built in Power BI to monitor and assess 
lending activities, track portfolio health, and support data-driven decisions.

---

## 📌 Problem Statement

Banks need real-time visibility into their loan portfolio — total applications, 
funded amounts, repayment status, and risk indicators. This dashboard provides 
a structured view of key lending KPIs across two interactive report pages.

---

## 📊 Dashboard Pages

### Page 1 — Summary
Tracks high-level KPIs with month-over-month comparisons:
- Total Loan Applications | Total Funded Amount | Total Amount Received
- Average Interest Rate | Average DTI (Debt-to-Income Ratio)
- Good Loan % (Fully Paid) vs Bad Loan % (Charged Off)

### Page 2 — Overview
Visual breakdown of lending trends:
- Monthly loan issuance trend (line chart)
- Loan purpose distribution (bar chart)
- State-wise loan geography (map)
- Loan grade, term, employment length, home ownership breakdowns

---

## 🖼️ Dashboard Preview

**Summary Page**
![Summary Dashboard](screenshots/summary_dashboard.png)

**Overview Page**
![Overview Dashboard](screenshots/overview_dashboard.png)

---

## 📁 Dataset

- **Source:** Financial Loan Data
- **Records:** 38,576 loan applications
- **Key Fields:** Loan Amount, Interest Rate, Loan Status, Purpose, Grade, 
  DTI, Annual Income, Issue Date, Address State

---

## 🛠️ Tools Used

| Tool | Usage |
|---|---|
| Power BI Desktop | Dashboard design, DAX measures, data modeling |
| Power Query | Data cleaning and transformation |
| Microsoft Excel | Source data |

---

## 🔍 Key Insights

- **83.3%** of loans are Fully Paid (Good Loans)
- **13.8%** are Charged Off (Bad Loans) — key risk segment
- **Debt Consolidation** is the #1 loan purpose (47% of all loans)
- Total portfolio value: **$435.7 Million**
- Average interest rate: **12%**

---

## 📂 Files in This Repo

| File | Description |
|---|---|
| `Bank_Loan_Analytics_Dashboard.pbix` | Power BI dashboard file |
| `Financial_loan_data.xlsx` | Raw dataset |
| `Problem_Statement.pptx` | Project requirements and design spec |
