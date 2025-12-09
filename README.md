
# 📊 **Power BI – Loan Recovery Dashboard**

This repository contains a complete **Loan Recovery Analytics Dashboard** built using **Power BI**.
It provides insights into customer behavior, loan performance, and recovery efficiency using interactive visuals, KPIs, slicers, and DAX measures.

---

## 🚀 **Project Overview**

This dashboard helps financial institutions understand:

* Total customers
* Loan amounts & recovery
* Risk segmentation
* Agent performance
* Monthly recovery trends
* Customer behavior analysis

The dashboard is divided into **three pages**:

---

## 📄 **Page 1 – Customer Loan Performance Dashboard**

Key visuals:

* Total Recovered by City
* Customer Status Distribution (Default / Partially Paid / Paid)
* Delay Bucket Analysis
* Slicers (City, Risk Score Range, Delay Bucket)

---

## 📄 **Page 2 – Agent Performance Dashboard**

Key metrics & visuals:

* Total Recovered by Agent
* Resolution Success Rate Gauge
* Average Contact Attempts
* Agent-specific performance table
* Slicers (Agent, Risk Score, Contact Attempts)
* Back/Next Page Navigation Buttons

---

## 📄 **Page 3 – Executive Insights Dashboard**

KPI Cards:

* **Total Customers**
* **Total Loan Amount**
* **Total Recovered**
* **Recovery Rate**

Trend Chart:

* **Total Recovered Over Time** (Line Chart)

This page provides high-level performance insights for management.

---

## 🔢 **DAX Measures Used**

```DAX
TotalCustomers = DISTINCTCOUNT(cleaned_loan_data[customer_id])

TotalLoanAmount = SUM(cleaned_loan_data[loan_amount])

TotalRecovered = SUM(cleaned_loan_data[TotalRecovered])

RecoveryRate = DIVIDE([TotalRecovered], [TotalLoanAmount])

AvgRiskScore = AVERAGE(cleaned_loan_data[risk_score])
```

These DAX formulas power all KPI cards and trend visuals.

---

## 🛠️ **Tools and Technologies**

* **Power BI Desktop**
* Power Query (Data Cleaning & Transformation)
* DAX (Metrics & Calculations)
* GitHub for version control

---

## 📁 **Repository Contents**

| File        | Description                  |
| ----------- | ---------------------------- |
| `.pbit`     | Power BI Template File       |
| `.pdf`      | Exported Dashboard           |
| `README.md` | Documentation                |
| `Assets/`   | Screenshots (if added later) |

---

## 📸 **Dashboard Preview**

<img width="1161" height="747" alt="image" src="https://github.com/user-attachments/assets/c2ea0b65-3a83-4a38-a053-f0a2d7008f9a" />
<img width="1157" height="740" alt="image" src="https://github.com/user-attachments/assets/4685ced5-0767-4f5f-aa44-76ae63523033" />
<img width="1161" height="744" alt="image" src="https://github.com/user-attachments/assets/4d094d54-69bb-4c4b-8086-55486872004b" />


---

## 📌 **How to Use**

1. Download the `.pbit` template from this repository
2. Open it in **Power BI Desktop**
3. Load data if prompted
4. Explore the interactive visuals


---

## 👤 **Author**

**Harsha**
Passionate about Data Analysis & Visualization
🔗 GitHub: [https://github.com/harsha88888](https://github.com/harsha88888)

