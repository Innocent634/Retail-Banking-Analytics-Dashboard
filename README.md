# Retail-Banking-Analytics-Dashboard
## Project Overview

This project demonstrates an end-to-end Power BI solution for analyzing retail banking operations.

The analysis focuses on:

- Retail Banking Transactions
- Customer Value Analysis
- Loan Portfolio Performance
- Credit Risk Assessment

The objective is to transform raw banking data into actionable business insights through interactive dashboards and executive KPIs.

## Business Objectives

The dashboards answer key banking questions such as:

• How much transaction volume does the bank process?

• Which branches generate the highest transaction value?

• What is the overall loan portfolio exposure?

• Which customer segments contribute the most value?

• What is the bank's credit risk exposure?

• Which regions have the highest concentration of risky loans?

## Dataset

The dataset contains information on:

- Customer Demographics
- Banking Transactions
- Loan Portfolio
- Customer Income
- Credit Risk Ratings
- Branch Information
- Regions
- Banking Channels

  ## Data Preparation

Power Query was used to:

- Remove duplicates
- Correct data types
- Handle missing values
- Create calculated columns
- Standardize text values
- Create date hierarchy

## Data Model

The project follows a star schema consisting of:

Fact Tables

- Banking Transactions
- Loan Portfolio

Dimension Tables

- Customer
- Date
- Branch
- Region

## Dashboards

# Retail Banking Transactions Dashboard


# Loan Portfolio & Credit Risk Dashboard


# Customer Value & Exposure Dashboard


## DAX Measures

Total Loan Portfolio =
SUM(Loan Portfolio[Loan Amount])

Average Loan Size =
AVERAGE(Loan Portfolio[Loan Amount])

Exposure at Risk =
CALCULATE(
SUM(Loan Portfolio[Loan Amount]),
Loan Portfolio[Risk Rating]="High")

## Key Insights

- Branch A processed the highest transaction volume.

- Digital banking channels accounted for over half of transactions.

- High-risk loans represented a notable share of the portfolio.

- Premium customers generated the highest exposure.

- Customers with higher incomes generally received larger loan amounts.

- Certain regions showed greater concentrations of credit risk.

## Recommendations

Increase monitoring of high-risk borrowers.

Expand digital banking services.

Develop retention programs for premium customers.

Review lending policies in high-risk regions.

Improve customer segmentation using predictive analytics.

## Skills Demonstrated

✔ Power BI

✔ Power Query

✔ DAX

✔ Data Modeling

✔ Financial Analytics

✔ Retail Banking Analytics

✔ Credit Risk Analysis

✔ KPI Development

✔ Dashboard Design

✔ Data Visualization

✔ Data Storytelling

## Tools

- Power BI
- Microsoft Excel
- Power Query
- DAX
- Git
- GitHub
  
