# 🛍️ Retail Sales & Customer Performance Optimization
### Consulting-Style Analytics Engagement | Power BI · DAX · Star Schema · RFM Segmentation

> **Simulating a Deloitte-style retail analytics project** — transforming raw transactional data into boardroom-ready business intelligence, strategic pricing recommendations, and customer retention frameworks.

---

## 📌 Project at a Glance

| Metric | Value |
|---|---|
| 💰 Total Revenue Analyzed | **₹11.95 Million** |
| 📈 Profit Margin Achieved | **35%** |
| 👥 Customers Segmented | **921+ at-risk customers identified** |
| 🚨 Revenue at Risk | **38% of total revenue** linked to Lost customers |
| 🔻 Avg. Discount Rate | **15%** — with zero proportional profit gain in high-discount bands |
| 🏗️ Data Model Type | **Star Schema** (Fact + 2 Dimension Tables) |
| 🧮 DAX Measures Built | RFM scoring, KPI measures, segment-level revenue analysis |

---

## 🎯 Business Problem

A retail business was running blanket discount campaigns and had no structured view of which customers were driving revenue — or quietly walking away.

**The questions this project answers:**
- Where is revenue leaking — and how much?
- Are discounts actually improving profitability, or just burning margin?
- Which customers are about to churn, and what's their revenue exposure?
- Where should the business focus its retention budget for maximum ROI?

---

## 🔍 Key Insights (Numbers That Matter)

### 💸 Revenue & Profitability
- **₹11.95M total revenue** analyzed across the full transaction dataset
- Business sustains a healthy **35% profit margin** — but this is under active threat
- Higher discount bands showed **no proportional increase in profit**, confirming margin dilution from undifferentiated discounting

### ⚠️ Customer Risk & Revenue Exposure
- **38% of total revenue** is tied to customers already classified as **Lost** — a critical revenue concentration risk
- **921 customers** flagged as **At Risk** using 90-day RFM inactivity logic, representing a significant churn pipeline
- Without intervention, this cohort represents a **material near-term revenue cliff**

### 🧠 RFM Segmentation Breakdown
Customers were classified into behavioral segments using **Recency, Frequency, and Monetary (RFM)** scoring built entirely in **DAX**:

| Segment | Business Implication |
|---|---|
| 🏆 Champions | Highest LTV — upsell and reward priority |
| 💛 Loyal Customers | Retention investment — protect at all costs |
| ⚡ At Risk (921) | Immediate win-back campaigns required |
| ❌ Lost | Targeted re-engagement; evaluate cost vs. LTV |

### 📉 Discount Impact Analysis
- Average discount rate sits at **15% across all transactions**
- Analysis revealed discounts beyond a threshold delivered **diminishing returns** — higher discount bands did not correlate with higher basket sizes or repeat purchase rates
- This directly supports the recommendation to shift from **blanket → targeted promotional strategy**

---

## 🏗️ Data Modeling & Technical Architecture

```
📦 Star Schema
│
├── 📊 Fact Table: Transactions
│     └── Transaction ID, Revenue, Profit, Discount, Quantity
│
├── 👤 Dimension: Customers
│     └── Customer ID, Segment, Region, RFM Score
│
└── 📅 Dimension: Calendar
      └── Date, Month, Quarter, Year (for time-intelligence DAX)
```

**DAX Engineering Highlights:**
- Custom **RFM scoring logic** using `CALCULATE`, `DATEDIFF`, `COUNTROWS`, `SUMX`
- **90-day inactivity flag** for at-risk classification
- **Dynamic segment-level revenue** measures for drill-through analysis
- **KPI cards** with conditional formatting for instant executive readability

---

## 📊 Dashboard Walkthrough

The Power BI dashboard was designed with a consulting-brief mindset — every visual answers a business question.

### Page 1 — Executive KPI Overview
![Dashboard Overview](Screenshot%202026-02-19%20184639.png)

### Page 2 — Customer Segmentation & RFM Analysis
![RFM Segmentation](Screenshot%202026-02-19%20184657.png)

### Page 3 — Discount Impact & Profitability Drill-Down
![Discount Analysis](Screenshot%202026-02-19%20184738.png)

---

## 🧠 Strategic Recommendations Delivered

| # | Recommendation | Business Impact |
|---|---|---|
| 1 | **Replace blanket discounting** with targeted, segment-specific promotions | Protect 35% margin; eliminate wasteful discount spend |
| 2 | **Launch win-back campaign** for high-value Lost customers | Recover portion of 38% at-risk revenue |
| 3 | **Proactively engage 921 At-Risk customers** before full churn | Prevent near-term revenue cliff |
| 4 | **Upsell Champions segment** — highest LTV, lowest acquisition cost | Maximize revenue from most engaged cohort |

---

## 🛠️ Tools & Technologies

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)

| Tool | Usage |
|---|---|
| **Power BI** | Data modeling, dashboard development, visualization |
| **DAX** | RFM scoring, KPI measures, time-intelligence calculations |
| **Excel** | Raw data preparation, validation, initial profiling |
| **Star Schema** | Relational data architecture for scalable reporting |

---

## 💼 Skills Demonstrated (Recruiter Checklist ✅)

- ✅ **Business Problem Framing** — translated vague retail challenges into structured analytical questions
- ✅ **End-to-End Data Modeling** — built production-ready Star Schema from raw transactional data
- ✅ **Advanced DAX Engineering** — custom RFM logic, time-intelligence, dynamic segmentation
- ✅ **KPI Dashboard Design** — executive-ready layout with conditional formatting and drill-through
- ✅ **Revenue Risk Quantification** — mapped 38% revenue exposure to a specific customer cohort
- ✅ **Consulting-Style Output** — insights → recommendations → actionable business strategy
- ✅ **Discount Sensitivity Analysis** — identified non-linear relationship between discount rate and profitability

---

## 📁 Repository Structure

```
📂 Retail-Sales-Customer-Performance-Optimization/
│
├── 📊 Business_Analytics_Dataset.xlsx    # Raw transactional data
├── 📈 job ready dashboard.pbix           # Full Power BI dashboard file
├── 🖼️ Screenshot 2026-02-19 184639.png   # Executive KPI overview
├── 🖼️ Screenshot 2026-02-19 184657.png   # RFM segmentation view
├── 🖼️ Screenshot 2026-02-19 184738.png   # Discount impact analysis
└── 📄 README.md                          # This file
```

---

## 👤 About the Author

**Adhitya Yellapu** — Data & Business Operations Analyst

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/adhitya-yellapu)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ADHITYAYELLAPU)
[![Portfolio](https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=google-chrome&logoColor=white)](https://adhityayellapu.github.io/Portfolio/)

---

*Self-initiated project designed to simulate consulting-grade retail analytics — the kind of work a Data Analyst at Deloitte, McKinsey, or a top-tier retail firm would deliver to C-suite stakeholders.*
