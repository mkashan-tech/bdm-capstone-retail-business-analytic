# 📈 Retail Profitability & Credit Risk Analytics

### IIT Madras Business Data Management (BDM) Capstone Project | Python | Business Analytics | Data-Driven Decision Making

⭐ **Achieved S Grade (90/100) in IIT Madras Business Data Management Capstone Project**

📊 Analyzed **2,625 credit transactions**, **1,105 category-wise sales records**, and **366 daily financial observations** to design a data-driven framework for improving profitability, cash flow quality, and credit risk management in a real retail business.

---

# 🏆 Academic Outcome

This project was completed as part of the **Business Data Management (BDM) Capstone Project** under the **BS in Data Science and Applications Program** at **Indian Institute of Technology Madras (IIT Madras)**.

**Final Grade: S (90/100)**

![IIT Madras BDM Project S Grade](images/iitm_bdm_project_s_grade.png)

---

# 📌 Executive Summary

Faiz General Store, a family-owned grocery retailer in Prayagraj, generated approximately ₹30 lakh annual revenue but faced increasing financial pressure due to customer credit defaults, declining cash flow quality, and heavy dependence on low-margin product categories.

This project applied business analytics techniques to identify the root causes of these issues, quantify their financial impact, and design practical business solutions. The analysis combined financial performance evaluation, category profitability analysis, customer risk assessment, and credit policy redesign to improve decision-making.

The outcome was a structured framework capable of reducing default exposure, improving liquidity, and increasing overall profitability.

## Key Results

| Metric | Value |
|---------|---------|
| Annualized Revenue (12-Month Dataset) | ₹32.8 Lakhs |
| Transaction-Level Revenue (5-Month Dataset) | ₹13.09 Lakhs |
| Credit Customers Evaluated | 105 |
| Credit Transactions Analyzed | 2,625 |
| Category-wise Sales Records | 1,105 |
| Daily Financial Records | 366 |
| Bad Debt Identified (5-Month Audit) | ₹40,184 |
| Projected Additional Profit (5-Month Simulation) | ₹53,798+ |
| Projected Profit Growth | +43.4% |
| Academic Grade | S (90/100) |

---

# 👥 Customer Reliability Scoring & Credit Policy Results

The reliability scoring model segmented 105 credit customers into four risk tiers and generated risk-based credit limits to support data-driven credit decisions and reduce default risk.

### 📊 Customer Tier Summary

| Risk Tier | Customer Count | Share (%) | Avg. Reliability Score | Avg. Recommended Credit Limit |
| :--- | :---: | :---: | :---: | :---: |
| 🟢 **Premium** | 59 | 56.2% | 85.6 | ₹1,712 |
| 🟡 **Standard** | 4 | 3.8% | 73.6 | ₹1,473 |
| 🟠 **Watchlist** | 14 | 13.3% | 56.4 | ₹1,127 |
| 🔴 **Cash Only** | 28 | 26.7% | 37.3 | ₹0 |

> 💡 **Key Operational Insight**
>
> While the Premium tier represents **56.2%** of customers and accounts for **₹0 in defaults**, the Cash Only tier generated **₹28,957 in defaults**, representing **72.1% of total bad debt**. This finding directly justified the introduction of a risk-based credit allocation framework.

---

# 🏢 Business Context

## Organization

**Faiz General Store**

* Family-owned grocery retailer
* Operating since 1995
* B2C retail business
* Serves daily household and consumer goods
* Approximate annual revenue of ₹30 lakh

Although revenue remained relatively stable, the business lacked structured systems for customer credit assessment, risk management, and profitability optimization.

---

# 🚨 Business Problems

The analysis identified three major challenges affecting business performance.

## 1. Credit Risk

* Increasing losses from customer defaults
* No formal customer credit evaluation system
* Credit allocation based primarily on experience and intuition

## 2. Cash Flow Deterioration

* Declining Cash-to-Credit Ratio
* Rising working capital pressure
* Reduced liquidity quality

## 3. Profitability Challenges

* Revenue concentrated in low-margin categories
* High-margin categories underutilized
* Inefficient product portfolio mix

---

# 🔒 Confidentiality Notice

This project was conducted using real business records from Faiz General Store.

To protect customer privacy and business-sensitive information, raw customer-level datasets, personally identifiable information (PII), and operational transaction records are not included in this public repository.

Only aggregated analytical outputs, dashboards, visualizations, methodologies, and business insights are shared.

---

# 🗂️ Data Overview

The analysis was performed on manually digitized operational records collected from store transactions.

## Dataset Summary

| Dataset                      | Period              | Records    |
| ---------------------------- | ------------------- | ---------- |
| Daily Financial Performance  | Sep 2024 – Aug 2025 | 366 Rows   |
| Category-wise Sales Analysis | Mar 2025 – Aug 2025 | 1,105 Rows |
| Credit Transactions          | Mar 2025 – Aug 2025 | 2,625 Rows |

## Data Included

- Revenue and sales performance metrics
- Cash and credit transaction records
- Product category information
- Customer credit history
- Outstanding balances and repayment behaviour
- Payment delays and default indicators
- Cost and profitability information

The combined datasets enabled financial analysis, profitability assessment, customer segmentation, credit risk modeling, and business performance evaluation.

## Data Preparation Highlights

- Missing repayment amounts were treated as ₹0.
- Missing repayment dates were imputed using a 15-day average repayment delay.
- Payment status labels were standardized before analysis.
- Data validation checks were performed before modeling and reporting.
  
---

# 🔍 Methodology

The project followed a complete business analytics workflow.

```text
Business Understanding
        ↓
Data Collection
        ↓
Data Digitization
        ↓
Data Cleaning
        ↓
Data Validation
        ↓
Exploratory Data Analysis
        ↓
Risk Modeling
        ↓
Business Recommendations
        ↓
Impact Projection
```

---

# 📉 Cash Flow Analysis

Financial health analysis revealed a continuous decline in the Cash-to-Credit Ratio, indicating worsening liquidity quality and increasing exposure to credit-related risks.

![Cash to Credit Ratio Trend](images/cash_to_credit_ratio_trend.png)

### Key Insight

Cash-to-Credit Ratio declined from:

**3.42 → 1.86**

placing the business in a financial warning zone.

---

# 🛒 Category Profitability Analysis

Revenue analysis showed that Staples contributed the largest share of sales but delivered relatively low profit margins. Higher-margin categories such as Personal Care and Snacks represented attractive growth opportunities.

![BCG Matrix](images/bcg_matrix.png)

### Key Insight

| Category      | Revenue Share | Profit Margin |
| ------------- | ------------- | ------------- |
| Staples       | 57.41%         | 9.25%         |
| Personal Care | 3.69%          | 26.56%        |
| Snacks        | 5.00%          | 20.91%        |

---

# 🤖 Customer Risk Modeling

To improve credit allocation decisions, a custom **Reliability Score (0–100)** was developed.
The score combined customer default behaviour and repayment delays to create a quantitative measure of creditworthiness for risk-based decision making.

## Model Structure

Reliability Score = (0.7 × Default Behaviour Score) + (0.3 × Payment Delay Score)

The model assigned greater weight to customer default behaviour (70%) than repayment delays (30%), reflecting the higher financial impact of unrecovered credit.

## Customer Segmentation

| Tier      | Score Range |
| --------- | ----------- |
| Premium   | 80+         |
| Standard  | 65–79       |
| Watchlist | 50–64       |
| Cash Only | <50         |

This segmentation framework enabled risk-based customer classification and structured credit decision-making.

---

# 📊 Customer Risk Insights

Analysis revealed that financial losses were highly concentrated among a small segment of customers.

### Major Findings

* 98% of financial losses originated from Watchlist and Cash Only customers
* Cash Only customers generated the majority of bad debt
* Credit risk was concentrated among a relatively small group of customers

![Reliability Tier Impact](images/reliability_tier_default_impact.png)

---

# 💳 Dynamic Credit Policy Framework

The project introduced a risk-based credit allocation system designed to align credit limits with customer reliability.

## Credit Limit Formula

```text
Credit Limit = Reliability Score × 20
```

## Business Benefits

* Reduced default exposure
* Improved credit discipline
* Better working capital allocation
* Scalable credit management framework

![Dynamic Credit Policy](images/dynamic_credit_limit_system.png)

---

# 💰 Projected Business Impact

Implementation of the proposed recommendations demonstrated substantial potential for improving profitability and reducing financial losses.

| Metric        | Current   | Projected |
| ------------- | --------- | --------- |
| Net Profit    | ₹1,23,804 | ₹1,77,602 |
| Net Margin    | 9.45%     | 13.50%    |
| Profit Growth | —         | +43.4%    |

## Estimated Additional Profit

### ₹53,798+

---

# 🛠 Skills Demonstrated

## Data Management

* Data Collection
* Data Digitization
* Data Validation
* Data Standardization
* Data Quality Assessment

## Data Preparation

* Data Cleaning
* Missing Value Handling
* Feature Engineering
* Data Aggregation
* Customer-Level Dataset Creation

## Business Analytics

* KPI Analysis
* Profitability Analysis
* Cash Flow Analysis
* Customer Segmentation
* Business Performance Evaluation

## Data Analysis

* Exploratory Data Analysis (EDA)
* Trend Analysis
* Financial Analysis
* Category Performance Analysis
* Descriptive Analytics

## Risk Analytics

* Credit Risk Assessment
* Reliability Scoring
* Customer Classification
* Risk-Based Credit Allocation

## Business Intelligence

* Executive Reporting
* Data Visualization
* Strategic Recommendation Design

## Tools & Technologies
* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab
* Google Sheets

## Version Control
* Git
* GitHub

---

# 📂 Repository Structure

```text
bdm-capstone-retail-business-analytics/
│
├── reports/
│   ├── Proposal_Report.pdf
│   ├── Midterm_Report.pdf
│   ├── Final_Report.pdf
│   └── IITM_Authorization_Letter.pdf
│
├── notebook/
│   └── IITM_BDM_Project_Colab_Notebook.ipynb
│
├── presentations/
│   ├── Academic_Presentation.pdf
│   └── Stakeholder_Presentation.pdf
│
├── images/
│   ├── iitm_bdm_project_s_grade.png
│   ├── executive_dashboard.png
│   ├── cash_to_credit_ratio_trend.png
│   ├── bcg_matrix.png
│   ├── reliability_tier_default_impact.png
│   └── dynamic_credit_limit_system.png
│
├── requirements.txt
└── README.md
```

---

# 🎯 Learning Outcomes

Through this project, I gained practical experience in:

* Solving real-world business problems using data
* Converting raw business records into analytical datasets
* Designing risk-based decision frameworks
* Translating analytical insights into business recommendations
* Communicating findings to technical and non-technical stakeholders
* Applying business analytics in a real operational environment

---

# 👨‍💻 Author

**Mohammad Kashan**

BS in Data Science and Applications
Indian Institute of Technology Madras

GitHub: [mkashan-tech](https://github.com/mkashan-tech)

LinkedIn: [mohammad-kashan-tech](https://linkedin.com/in/mohammad-kashan-tech)

---

⭐ If you found this project interesting, feel free to explore the reports, notebook, visualizations, and presentations included in this repository.
