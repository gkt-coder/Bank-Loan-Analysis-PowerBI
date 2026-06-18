# 📊 Bank Loan Analysis Dashboard | Power BI Project

## Overview

The Bank Loan Analysis Dashboard is a Business Intelligence solution developed using Power BI to analyze loan applications, approval performance, customer demographics, and risk assessment. The dashboard helps financial institutions monitor lending operations, identify risk patterns, and make data-driven decisions.

This project transforms raw banking data into actionable insights through interactive visualizations, KPI tracking, and advanced analytical reporting.

---

## Business Problem

Banks process a large number of loan applications every month. Without proper analytics, it becomes difficult to:

* Track loan approval and rejection rates
* Identify high-risk customers
* Analyze customer demographics
* Understand rejection reasons
* Monitor regional loan performance
* Improve lending strategies

This dashboard provides a centralized analytical platform to support better lending decisions and risk management.

---

## Business Objectives

* Monitor overall loan performance
* Analyze approval and rejection trends
* Identify high-risk applicants
* Improve lending decisions
* Reduce loan default risk
* Understand customer behavior
* Enhance operational efficiency

---

## Tools & Technologies

* Power BI
* DAX (Data Analysis Expressions)
* Power Query
* Microsoft Excel

---

## Dashboard Pages

### Executive Summary Dashboard

* Total Applications
* Approved Loans
* Rejected Loans
* Approval Rate
* Rejection Rate
* Monthly Loan Trends
* State-wise Performance

### Customer Analysis Dashboard

* Gender Distribution
* Age Group Analysis
* Income Analysis
* Employment Type Analysis
* Credit Score Analysis

### Risk Analysis Dashboard

* Risk Category Distribution
* High Risk Customers
* Medium Risk Customers
* Low Risk Customers
* Risk vs Approval Analysis

---

## Key KPIs

| KPI                  | Description                      |
| -------------------- | -------------------------------- |
| Total Applications   | Total loan applications received |
| Approved Loans       | Number of approved applications  |
| Rejected Loans       | Number of rejected applications  |
| Approval Rate        | Percentage of approved loans     |
| Rejection Rate       | Percentage of rejected loans     |
| Average Credit Score | Average customer credit score    |

---

## DAX Measures Used

```DAX
Total Applications = COUNT(Loan_ID)

Approved Loans =
CALCULATE(
    COUNT(Loan_ID),
    Loan_Status = "Approved"
)

Rejected Loans =
CALCULATE(
    COUNT(Loan_ID),
    Loan_Status = "Rejected"
)

Approval Rate =
DIVIDE([Approved Loans], [Total Applications], 0) * 100
```

---

## Key Business Insights

* Customers with higher credit scores have higher approval rates.
* Low-income applicants show higher rejection rates.
* Certain states contribute significantly to loan approvals.
* Risk level directly impacts approval decisions.
* Rejection patterns help optimize lending policies.

---

## Business Benefits

### Operational Benefits

* Faster reporting
* Reduced manual effort
* Better loan tracking
* Improved data visibility

### Strategic Benefits

* Enhanced risk management
* Better customer segmentation
* Improved decision-making
* Increased business efficiency

---

## Project Files

* Bank_Loan_Pbi.pbix
* Project Documentation
* Project Presentation (PPT)
* Dashboard Screenshots

---

## Future Enhancements

* Loan Default Prediction using Machine Learning
* Real-Time Dashboard Monitoring
* Predictive Risk Scoring
* Automated Alert System

---

## Author

**Ghanshyam Kumar**

Aspiring Data Analyst | Power BI Developer | SQL | Python | Excel

GitHub: https://github.com/gkt-coder

LinkedIn: https://www.linkedin.com/in/ghanshyamkumar01/
