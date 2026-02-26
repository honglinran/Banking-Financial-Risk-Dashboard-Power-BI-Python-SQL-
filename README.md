# Banking Financial Risk Dashboard (Power BI + Python + SQL)

## Overview
This project is an end-to-end data analytics case study where I built an interactive **Banking Financial Risk Dashboard** to explore **loan and deposit insights** across different customer segments.

The workflow covers:
- Loading and exploring a CSV dataset in **Python**
- Transforming and aggregating data using **SQL**
- Building a multi-page dashboard in **Power BI** with **DAX measures**
- Designing the dashboard layout first in **Canva**, then implementing it in Power BI

## Project Goals
- Turn raw banking data into clear KPIs and segment-level insights
- Compare **Loan vs Deposit** performance over time and by customer groups
- Practice both approaches to metric creation:
  - **SQL aggregations** (preparing data before Power BI)
  - **DAX measures** (calculating metrics directly inside Power BI)

## Dataset
The dataset contains the following main columns:

- **Bank Loans**
- **Checking Accounts**
- **Saving Accounts**
- **Foreign Currency Account**
- **Business Lending**
- **Properties Owned**
- **Risk Weighting**
- **BRId** (Banking Relationship ID)
- **GenderId**
- **IAId** (Institutional Advisor ID)
- **Total Loan**

> Note: In Power BI, I transformed coded fields (e.g., `GenderId = 1/2`) into readable labels (`Female/Male`) and extracted **Year** from date fields for time-based filtering.

## Tools & Technologies
- **Python** (Pandas, NumPy, Matplotlib/Seaborn) — EDA & data understanding  
- **SQL** — data cleaning / aggregation / modeling  
- **Power BI** — dashboard, data model, and interactive reporting  
- **DAX** — measures and KPI calculations  
- **Canva** — dashboard layout planning and design

## Workflow Summary

### 1) Python (EDA)
- Loaded the CSV dataset
- Checked missing values, distributions, and basic statistics
- Explored relationships related to risk and financial indicators

### 2) SQL (Transformations + Aggregations)
- Built aggregation queries (e.g., SUM/grouping) to create reporting-ready tables
- Connected SQL to Power BI for scalable analysis

### 3) Power BI (Dashboard + DAX)
- Built measures for KPIs (loans, deposits, checking/saving amounts, etc.)
- Created slicers for interactive exploration:
  - **Year**
  - **Gender**
  - **Banking Relationship (BR)**
  - **Institutional Advisor (IA)**
- Used visuals:
  - Cards, bar charts, donut charts, slicers

### 4) Dashboard Design (Canva → Power BI)
- Sketched the page layouts in Canva first
- Implemented the final design and navigation inside Power BI

## Dashboard Pages
### ✅ Summary
High-level KPIs such as:
- Total Clients
- Total Loan
- Total Deposit
- Checking Accounts
- Saving Accounts
- Business Lending

### ✅ Loan Analysis
Loan-focused insights and segmentation such as:
- Bank Loan by Banking Relationship (BR)
- Bank Loan by Occupation
- Bank Loan by Income Band
- Bank Loan by Nationality

### ✅ Deposit Analysis
Deposit-focused insights and segmentation such as:
- Bank Deposit by Banking Relationship (BR)
- Bank Deposit by Occupation
- Bank Deposit by Income Band
- Bank Deposit by Nationality

## Key Learning
This project was also my learning journey into a new industry (banking).  
While wrangling the data, I often tested multiple approaches to solve the same problem:
- **SQL aggregations** vs **DAX measures** in Power BI  
This helped me understand trade-offs and choose the most suitable method depending on the use case.

