
# Retail Profitability & Credit Risk Analytics

![IIT Madras](https://img.shields.io/badge/IIT%20Madras-BS%20Data%20Science-blue)
![Grade](https://img.shields.io/badge/Grade-S%20(90/100)-green)
![Python](https://img.shields.io/badge/Python-3.10+-yellow)
![Status](https://img.shields.io/badge/Project-Completed-success)

### Independent Business Analytics Case Study | Primary Research | Data-Driven Strategy for a ₹30L Revenue SME

**IIT Madras BS in Data Science and Applications**  
Business Data Management (BDM) Capstone — Independent Research Project  
**Final Grade: S (90/100)**

---

## Business Impact at a Glance

| Metric | Before | After (Projected) | Change |
|---|---|---|---|
| Net Profit Margin | 9.45% | **13.50%** | **+405 bps** |
| Bad Debt (5 months) | ₹40,184 | ~₹11,000 | **-72% immediate** |
| Additional Profit (5 months) | — | **₹53,798+** | **+43.4%** |

> **Liquidity Context:** Cash-to-Credit ratio declined from 3.42 to 1.86 (Warning Zone). The Safe Zone threshold is >2.5. With 72% of high-risk credit frozen and cash sales incentivized via the 2% discount, the ratio is structurally positioned to recover toward the Safe Zone.

**Key Insight:** 72% of credit defaults originated from just 26.7% of customers (Cash Only tier), with 98% of all defaults concentrated in only 40% of customers (Watchlist + Cash Only combined). A risk-based credit policy eliminates the majority of the leak while preserving relationships with reliable customers.

---

## Problem Statement

**Faiz General Store** (Prayagraj) — a family-owned grocery retailer generating ~₹30 lakh annual revenue — faced three interconnected challenges despite stable sales:

1. **Profit Leak** — Critically low 9.45% net margin with ₹40,184 in bad debt over 5 months
2. **Liquidity Crisis** — Cash-to-Credit ratio declined from 3.42 to 1.86 (entered warning zone)
3. **Volume vs Value Trap** — 57% of revenue came from low-margin Staples (9.25% margin), while high-margin categories (Personal Care 26.56%, Snacks 20.91%) remained underutilized

---

## Consulting Approach

This project was executed as an end-to-end independent consulting engagement with structured IITM oversight:

| Phase | Deliverable | IITM Review |
|---|---|---|
| Phase 1: Discovery & Diagnosis | Proposal Report | Approved |
| Phase 2: Analytics & Root-Cause | Midterm Report | Approved |
| Phase 3: Solution Design | Final Report + Presentations | Approved — S Grade |

**Phase 1: Discovery & Diagnosis**  
Primary data collection from operational registers + stakeholder discussions with the business owner. Financial health and liquidity trend diagnosis.

**Phase 2: Analytics & Root-Cause**  
Customer risk segmentation, portfolio analysis using BCG Matrix, and quantification of the ₹40,184 bad debt concentration.

**Phase 3: Solution Design**  
Custom Reliability Score (0–100) + Dynamic Credit Policy + Category mix optimization strategy.

**Phase 4: Impact Projection & Roadmap**  
3-phase implementation plan with projected **₹53,798+ additional profit (+43.4% growth)** and net margin expansion from **9.45% to 13.5%**.

---

## Primary Research & Data Collection

All analysis was built on **manually digitized operational records** collected directly from the store:

| Dataset | Period | Records | Collection Method |
|---|---|---|---|
| Daily Financial Performance | Sep 2024 – Aug 2025 | 366 | Manual digitization |
| Category-wise Sales | Mar 2025 – Aug 2025 | 1,105 | Primary transcription |
| Credit Transactions | Mar 2025 – Aug 2025 | 2,625 | Manual entry + validation |

**Data Quality Measures**
- Cross-validated 5 festival closing days (zero sales confirmed with owner)
- Imputed 48 missing payment dates using owner consultation + 15-day average delay logic
- Standardized inconsistent payment status labels

**Confidentiality Notice**  
Raw customer-level data and personally identifiable information are excluded from this public repository to protect privacy and business sensitivity. Only aggregated outputs, visualizations, methodologies, and insights are shared.

---

## Solution Framework

### 1. Customer Reliability Score (0–100)

Weighted model combining default behaviour and payment delays:

```
Reliability Score = (0.7 × Default Behaviour Score) + (0.3 × Payment Delay Score)
```

**Segmentation Results**

| Risk Tier | Score Range | Customers | Share | Avg. Recommended Credit Limit | Default Contribution |
|---|---|---|---|---|---|
| Premium | ≥ 80 | 59 | 56.2% | ₹1,712 | ₹0 (0%) |
| Standard | 65–79 | 4 | 3.8% | ₹1,473 | ₹854 (2%) |
| Watchlist | 50–64 | 14 | 13.3% | ₹1,127 | ₹10,373 (26%) |
| Cash Only | < 50 | 28 | 26.7% | ₹0 | ₹28,957 (72%) |

### 2. Dynamic Credit Policy (Owner Controlled Framework)

```
Credit Limit = Reliability Score × 20
```

- **Immediate freeze** of credit for all 28 "Cash Only" customers → eliminates **72% of defaults** with zero assumptions
- **Scalable limits** for the remaining 77 reliable customers → preserves revenue and relationships
- **Owner-controlled multiplier** (currently 20×) allows the business owner to adjust credit exposure based on market conditions while maintaining score integrity

### 3. Category Strategy (BCG Matrix)

- **Cash Cow:** Staples — maintain traffic, do not over-invest
- **Question Marks:** Personal Care & Snacks — promote aggressively (especially on weekends with +22% traffic)
- **Stars:** Beverages, Dairy & Bakery, Cleaning — stable high performers

---

## Strategic Recommendations (3-Phase Roadmap)

**Phase 1: Stop the Bleeding (Days 1–30)**
- Freeze credit for 28 Cash Only customers
- Launch temporary 2% "Fair Play" cash discount to manage transition and prevent churn
- **Goal:** Eliminate 72% of default exposure immediately

**Phase 2: Drive Profitability (Months 1–6)**
- Roll out dynamic credit limits (Score × 20) for 77 reliable customers
- Execute portfolio shift through Staples + high-margin bundles
- Weekend-focused promotions on Personal Care & Snacks
- **Goal:** Improve overall margin mix by +1.5%

**Phase 3: Build Loyalty (Months 6+)**
- Formalize Premium-tier rewards program
- Use Staples as loss-leader for footfall while growing high-margin categories
- **Goal:** Sustainable long-term growth

**Projected 5-Month Impact:** Net Profit ₹1,23,804 → **₹1,77,602 (+43.4%)** | Net Margin 9.45% → **13.5%**

> **Default Reduction Trajectory:** 72% reduction is immediate and guaranteed (Cash Only freeze). With consistent enforcement of dynamic limits and payment reminders for Watchlist/Standard tiers, the projected path reaches **85% total default reduction**.

---

## Key Visualizations

### Cash-to-Credit Ratio Trend (12 Months)
![Cash to Credit Ratio](images/cash_to_credit_ratio_trend.png)

### Category Strategy Matrix (BCG)
![BCG Matrix](images/bcg_matrix.png)

### Customer Reliability Tier Impact
![Reliability Tier Impact](images/reliability_tier_default_impact.png)

### Dynamic Credit Limit System
![Dynamic Credit Limit](images/dynamic_credit_limit_system.png)

---

## Skills Demonstrated

| Competency | Application in Project |
|---|---|
| Primary Research | Collected, digitized & validated 3 operational datasets from a live business |
| Financial Analysis | Waterfall P&L, liquidity ratios, margin analysis, cash-flow diagnostics |
| Risk Modeling | Custom 0–100 Reliability Score with business-interpretable weights |
| Strategic Frameworks | BCG Matrix for portfolio optimization |
| Stakeholder Communication | Separate Academic & Stakeholder presentations tailored to audience |
| Data Storytelling | Translated ₹40k defaults into "24.5% of Gross Profit wiped out" narrative |

**Tools:** Python (Pandas, NumPy, Matplotlib, Seaborn), Google Colab, Google Sheets, Git/GitHub

---

## Deliverables

| Audience | Document | Focus |
|---|---|---|
| Academic | Academic Presentation | Methodology, process, grading criteria |
| Business | Stakeholder Presentation | Financial impact, roadmap, risk mitigation |
| Documentation | Proposal → Midterm → Final Report | Complete project lifecycle with IITM approvals |

All reports and presentations are available in the `reports/` and `presentations/` folders.

---

## Academic Context

This project was completed as the **Business Data Management Capstone** under the BS in Data Science and Applications program at **Indian Institute of Technology Madras**.

It is an **independent research project** requiring students to identify a real business, collect primary data, diagnose problems, and deliver actionable insights. The project progressed through a **3-stage gated approval process**: Proposal → Midterm → Final, with each phase requiring IITM faculty approval before proceeding. An official IITM authorization letter supported primary data collection from the business.

**Final Grade: S (90/100)**

---

## Repository Structure

```
├── reports/
│   ├── Proposal_Report.pdf
│   ├── Midterm_Report.pdf
│   ├── Final_Report.pdf
│   └── IITM_Authorization_Letter.pdf
├── notebook/
│   └── IITM_BDM_Project_Colab_Notebook.ipynb
├── presentations/
│   ├── Academic_Presentation.pdf
│   └── Stakeholder_Presentation.pdf
├── images/
│   ├── cash_to_credit_ratio_trend.png
│   ├── bcg_matrix.png
│   ├── reliability_tier_default_impact.png
│   └── dynamic_credit_limit_system.png
├── requirements.txt
└── README.md
```

---

## Author

**Mohammad Kashan**  
BS in Data Science and Applications — IIT Madras

[GitHub](https://github.com/mkashan-tech) · [LinkedIn](https://linkedin.com/in/mohammad-kashan-tech)

---

If you found this project useful, feel free to star the repository.
```
