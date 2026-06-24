# Loan Default Risk Analysis Dashboard

## Project Overview

This project is a professional **FinTech / Banking Risk Analytics Dashboard** built to analyze loan default risk, borrower profiles, credit behavior, financial performance, and portfolio health.

The dashboard helps financial institutions identify high-risk borrowers, monitor default patterns, and make data-driven lending decisions.

This project is designed as a portfolio project for **Data Analyst**, **BI Developer**, and **Business Intelligence** roles.

---

## Business Problem

Loan default is one of the most important challenges for banks, NBFCs, and lending companies. A high default rate can directly impact profitability, risk exposure, and portfolio quality.

This dashboard analyzes borrower and loan data to answer key business questions:

- What is the overall default rate?
- Which borrower segments are most risky?
- How does income impact default probability?
- Which employment type has the highest default risk?
- How does DTI ratio affect repayment behavior?
- Which credit score groups contribute most to portfolio risk?
- What actions can reduce future loan defaults?

---

## Dashboard Preview

### Overview
![Executive Overview](01_Overview.png)

### Risk Analysis
![Risk Analysis](02_Risk_Analysis.png)

### Customer Analysis
![Customer Analysis](03_Customer_Analysis.png)

### Financial Analysis
![Financial Analysis](04_Financial_Analysis.png)

### Default Prediction
![Default Prediction](05_Default_Prediction.png)

---

## Dashboard Pages

### 1. Executive Overview

Provides a high-level summary of the loan portfolio.

Key metrics include:

- Total Loans
- Total Loan Amount
- Average Loan Amount
- Default Rate
- Non-Default Rate
- Average Interest Rate
- Average Credit Score
- Portfolio Health Score

---

### 2. Risk Analysis

Analyzes default risk across borrower and loan characteristics.

Visuals include:

- Default Rate by Employment Type
- Default Rate by Loan Purpose
- Default Rate by Age Group
- Default Rate by DTI Group
- High-Risk Borrower Segments
- Critical-Risk Borrower Segments

---

### 3. Customer Analysis

Focuses on customer profile and borrower behavior.

Visuals include:

- Borrower Count by Age Group
- Default Rate by Income Group
- Borrower Distribution by Education
- Mortgage Status Analysis
- Marital Status Analysis
- Co-Signer and Dependents Analysis

---

### 4. Financial Analysis

Analyzes loan amount, interest rate, and portfolio value.

Visuals include:

- Average Loan Amount by Education
- Total Loan Amount Over Years
- Total Loans by Interest Rate Group
- Default Rate by Income Group
- Minimum and Maximum Loan Amount
- Minimum and Maximum Interest Rate
- Average Loan Amount

---

### 5. Default Prediction

Highlights risk probability and borrower default patterns.

Visuals include:

- Overall Default Probability
- Young Borrower Risk
- Senior Borrower Risk
- Default Rate by Age Group
- Default Rate by Income Group
- Default Rate by DTI Group
- Segment-Wise Risk Analysis

---

## Dataset Description

The dataset contains borrower-level and loan-level information used to analyze loan default behavior.

| Column | Description |
|---|---|
| Loan ID | Unique identifier for each loan |
| Age | Age of the borrower |
| Income | Annual income of the borrower |
| Loan Amount | Loan amount sanctioned to borrower |
| Credit Score | Borrower credit score |
| Months Employed | Employment duration in months |
| Number of Credit Lines | Number of existing credit lines |
| Interest Rate | Interest rate charged on loan |
| Loan Term | Loan repayment duration |
| DTI Ratio | Debt-to-income ratio |
| Education | Education level of borrower |
| Employment Type | Borrower employment status |
| Marital Status | Marital status of borrower |
| Has Mortgage | Mortgage status of borrower |
| Has Dependents | Dependent status |
| Loan Purpose | Purpose of loan |
| Has Co-Signer | Co-signer availability |
| Default | Target variable indicating loan default |

---

## Data Analysis Process

The following steps were performed before building the dashboard:

- Imported and reviewed the loan default dataset
- Checked column names, data types, and field meanings
- Identified numerical and categorical variables
- Cleaned and transformed data using Power Query
- Created calculated columns for segmentation
- Created DAX measures for KPIs
- Built risk categories based on credit score and borrower behavior
- Designed dashboard pages for business storytelling
- Generated insights and recommendations from the analysis

---

## Key KPIs

| KPI | Description |
|---|---|
| Total Loans | Total number of loans in the portfolio |
| Total Loan Amount | Total value of issued loans |
| Average Loan Amount | Average sanctioned loan amount |
| Default Rate | Percentage of loans defaulted |
| Non-Default Rate | Percentage of performing loans |
| Average Interest Rate | Average interest rate across loans |
| Average Credit Score | Average borrower credit score |
| Average DTI Ratio | Average debt-to-income ratio |
| High-Risk Borrowers | Borrowers in high-risk credit score range |
| Critical-Risk Borrowers | Borrowers with very low credit score |
| Portfolio Health Score | Composite view of portfolio quality |

---

## Risk Segmentation

Borrowers were segmented into risk categories based on credit score and default behavior.

| Risk Category | Criteria |
|---|---|
| Low Risk | Credit Score 700+ |
| Medium Risk | Credit Score 600–699 |
| High Risk | Credit Score 500–599 |
| Critical Risk | Credit Score below 500 |

Additional risk factors considered:

- Low income
- High DTI ratio
- Unemployment
- No co-signer
- Young borrower age group
- Business loan purpose

---

## Key Insights

- Borrowers aged **18–25** show the highest default risk.
- Borrowers aged **56–69** show the lowest default risk.
- Borrowers with income below **$30K** have the highest default probability.
- Unemployed borrowers show higher default risk compared to full-time borrowers.
- Higher DTI ratio increases default probability.
- Borrowers without a co-signer show higher risk exposure.
- Home loans show comparatively lower default risk.
- Low credit score borrowers represent the most critical risk segment.

---

## Business Recommendations

Based on the analysis, the following actions are recommended:

1. **Strengthen underwriting for young borrowers**
   - Borrowers aged 18–25 show high default probability.
   - Additional income and employment verification should be applied.

2. **Monitor low-income borrowers**
   - Borrowers earning below $30K have the highest default risk.
   - Loan limits and approval thresholds should be reviewed for this group.

3. **Encourage co-signers for high-risk profiles**
   - Borrowers without co-signers show higher risk exposure.
   - Co-signers can help reduce repayment risk.

4. **Control high DTI exposure**
   - Borrowers with high debt-to-income ratios should be monitored closely.
   - DTI-based approval rules can improve portfolio quality.

5. **Reduce exposure to critical-risk borrowers**
   - Borrowers with credit scores below 500 require stricter risk checks.
   - This segment should be monitored with early-warning indicators.

6. **Expand low-risk segments**
   - Senior borrowers and high-credit-score customers show better repayment behavior.
   - These segments can be targeted for safer portfolio growth.

---

## Tools Used

- Power BI
- SQL
- Python
- DAX
- Power Query
- Data Modeling
- Data Cleaning
- Data Visualization
- Business Intelligence
- Risk Analytics

---

## Skills Demonstrated

- Data Cleaning
- Data Transformation
- SQL Querying
- Python Data Analysis
- Power Query Transformation
- DAX Measure Creation
- KPI Development
- Dashboard Design
- Credit Risk Analysis
- Borrower Segmentation
- Financial Analysis
- Business Insight Generation
- BI Storytelling
- Portfolio Presentation

---

## Project Outcome

This dashboard helps financial institutions:

- Identify high-risk borrowers
- Understand loan default behavior
- Monitor portfolio performance
- Reduce risk exposure
- Improve credit approval strategy
- Make data-driven lending decisions

---
** Anurag Tijare **
Data Analyst / BI Developer
