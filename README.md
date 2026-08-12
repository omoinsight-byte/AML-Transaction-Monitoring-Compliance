# AML Transaction Monitoring & Compliance Dashboard

## Project Overview

This project explores how transaction and compliance data can be analysed to identify financial crime risk, prioritise investigations and support compliance decision-making.

The project combines **SQL** for data analysis and querying with **Microsoft Power BI** for interactive reporting and dashboard development.

## Business Question

> How can transaction and compliance data be used to identify high-risk activity and prioritise cases for investigation?

## Objectives

The analysis aims to:

- Identify high-risk transactions and customers
- Analyse transaction values and risk scores
- Investigate patterns in compliance cases
- Identify countries associated with higher risk
- Examine reasons for transaction alerts
- Prioritise cases requiring further investigation
- Develop an interactive compliance monitoring dashboard

## Tools & Technologies

- **SQL Server / SQL Server Management Studio (SSMS)**
- **Microsoft Power BI**
- **DAX**
- **Microsoft Excel**
- **Power Query**

## Dataset

The project uses a structured dataset containing transaction, customer, country-risk and compliance-case information.

Key data areas include:

- Transactions
- Customers
- Compliance Cases
- Country Risk
- Risk Scores
- Transaction Types
- Alert Reasons
- Case Status and Resolution

## SQL Analysis

SQL is being used to investigate questions including:

1. How many transactions are classified as high risk?
2. What is the total value of high-risk transactions?
3. Which countries have the highest transaction risk?
4. Which transaction types generate the most alerts?
5. What are the most common alert reasons?
6. How many compliance cases remain open?
7. Which cases have the highest risk scores?
8. Which customers are associated with multiple alerts?
9. How does transaction activity vary over time?
10. Which cases should be prioritised for investigation?

The SQL analysis investigates transaction and compliance risk using queries designed to support AML monitoring and investigation prioritisation.

The analysis covers:
- Transaction risk classification
- Transaction values and volumes
- High-risk activity
- Compliance case status
- Alert reasons
- Customer activity
- Country risk
- Investigation priorities

## Power BI Dashboard

The Power BI dashboard will provide an interactive view of:

- Total transaction value
- Transaction volume
- High-risk transactions
- Average risk score
- Open compliance cases
- Risk-level distribution
- Geographic risk
- Alert reasons
- Investigation priorities

## Business Recommendations

Based on the analysis, organisations could:

1. Prioritise high-risk transactions for enhanced investigation.
2. Monitor customers who repeatedly trigger AML alerts.
3. Apply enhanced due diligence to customers associated with elevated risk.
4. Increase monitoring of higher-risk jurisdictions.
5. Investigate recurring suspicious behaviours such as structuring and unusually high-value transactions.
6. Use automated risk scoring and dashboards to support ongoing transaction monitoring.

## Skills Demonstrated

- SQL querying and data analysis
- Power BI dashboard development
- DAX measures
- Data visualisation
- Risk and compliance analysis
- AML transaction monitoring
- Business question development
- Data-driven recommendations
- Analytical storytelling


## Key Measures

Example Power BI measures include:

```DAX
Total Transactions =
COUNTROWS(Transactions)
