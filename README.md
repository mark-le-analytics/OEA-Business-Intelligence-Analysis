# 🏢 Office Essentials Australia — Business Intelligence Analysis




## 📌 Project Overview

This project delivers a comprehensive Business Intelligence analysis for
Office Essentials Australia (OEA), a national supplier of office products
serving corporate clients, SMEs, and small businesses across Australia.

The objective is to transform six years of transactional sales data
(2019–2024) into actionable insights across four key business dimensions:
overall business health, customer behaviour, product performance, and
customer lifetime value.
## 🎯 Objectives

- Assess overall business health and identify performance trends
- Segment customers using RFM analysis and profitability tiers
- Evaluate product and margin performance across categories
- Model Customer Lifetime Value (CLV) and analyse churn patterns
- Deliver data-driven strategic recommendations

## 📊 Dashboard Preview
> The dashboards below highlight key visualisations from the analysis.
> For the complete set of charts and detailed findings, refer to the
The Tableau dashboard https://public.tableau.com/views/OfficeEssentialsAustraliaBusinessIntelligenceAnalysis-Dashboard/2_1RFMDashBoard?:language=fr-FR&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

**Page 1: Business Health Overview**
- KPI summary, YoY profit comparison, regional quadrant analysis,
  market trends and what-if scenario modelling
  <img width="1892" height="1297" alt="image" src="https://github.com/user-attachments/assets/06d87060-f88b-43d9-b122-b8e5315a6fe0" />
  <img width="1518" height="1296" alt="image" src="https://github.com/user-attachments/assets/6bdd7615-add7-41da-b56c-ebb1c8376dd3" />
<img width="1995" height="611" alt="image" src="https://github.com/user-attachments/assets/eb4b9625-2463-40bf-b065-0074c58d4fea" />



**Page 2: Customer Segmentation**
- RFM segment distribution, profitability tier analysis,
  Pareto contribution chart, product preference heatmaps
<img width="1995" height="658" alt="image" src="https://github.com/user-attachments/assets/bea6794b-80e3-42fe-a045-536aca42ef09" />
<img width="2559" height="1548" alt="image" src="https://github.com/user-attachments/assets/91337a65-6b53-4a8c-96e7-d1101609a067" />
<img width="2559" height="1554" alt="image" src="https://github.com/user-attachments/assets/f6750b5d-4124-43f7-940e-b83106547150" />



**Page 3: Product Performance**
- Sales vs margin quadrant, margin segment matrix,
  top clients per product line, price elasticity analysis
<img width="1276" height="794" alt="image" src="https://github.com/user-attachments/assets/2fb58508-1f69-445e-8250-52bfa61ed80d" />
<img width="2511" height="1182" alt="image" src="https://github.com/user-attachments/assets/84620c84-85ff-471f-9d96-d4ed91591f37" />


**Page 4: CLV and Churn**
- CLV trend over time, CLV vs frequency segmentation,
  3-month churn rate by state, cohort retention analysis
<img width="1301" height="816" alt="image" src="https://github.com/user-attachments/assets/ad7b6fcb-f956-47bd-b80b-8f953cc0fe8f" />

<img width="1386" height="856" alt="image" src="https://github.com/user-attachments/assets/425a3962-47eb-4eec-a90a-d523fad5a7db" />


## 🛠️ Tools and Technologies

| Tool | Purpose |
|---|---|
| Tableau | Dashboard development and visualisation |
| Power BI | Supporting analysis and reporting |
| Excel | Data cleaning and preparation |
| RFM Modelling | Customer segmentation |
| DAX / Calculated Fields | Custom metrics and KPIs |


## 📊 Dataset

- **Source:** OEA internal transactional sales data (2019 to 2024)
- **Tables:** 3 relational tables — Transaction, Product, and Client
- **Volume:** Multi-year B2B transactions across all Australian states

A full data dictionary is available in `data_dictionary.xlsx`.

**Data Quality Actions Taken:**
- Removed 7 duplicate transaction rows
- Corrected margin and cost discrepancies exceeding $2
- Standardised inconsistent State and Country fields
- Removed 40 zero-margin transactions
- Excluded unreliable Sales Quantity field from volume analysis


## 📈 Key Analysis Areas

### 1. Overall Business Health
- Total 2024 profit of $2,328,328 representing a 4.6% year-on-year increase
- Consistent seasonal peaks in Q4 (October) driven by corporate
  procurement cycles and financial year-end spending
- Significant underperformance in Furniture and Technology categories
  relative to targets

### 2. Regional Performance
- WA and Queensland identified as high-growth, high-sales markets
- NSW and Victoria show market maturity with high volume but
  constrained growth
- ACT and NT represent untapped high-growth potential
- Tasmania and SA underperform across both revenue and growth metrics
- City-level insight: smaller cities such as Albury and Fremantle
  outperform major metros like Sydney and Brisbane

### 3. Customer Segmentation (RFM Analysis)
- Six behavioural segments: Champions, Loyal, Promising,
  Need Attention, New, and Lost
- Loyal and Promising clients represent nearly 50% of the customer
  base and contribute over $48M in combined sales
- Champions show high value per transaction despite lower frequency
- Lost and Need Attention segments flagged as churn risks

### 4. Customer Profitability Tiers
- Pareto analysis confirms top 20% of clients drive over 80% of profit
- Key top-tier clients: Quality First Services, Twin Peaks,
  Highway Heroes
- Bottom 5% of clients identified as unprofitable despite
  regular purchasing

### 5. Product Performance
- Paper is the highest-margin, highest-volume product and serves
  as OEA's profitability anchor
- Chairs and Phones drive the highest revenue but at low margins
- Accessories, Tables, and Fasteners offer strong margins
  but low sales volume, representing bundling opportunities
- Machines and Copiers show consistent decline linked to
  digitisation and remote work trends

### 6. Price Sensitivity and Demand Elasticity
- Technology products show high price elasticity due to
  abundant substitutes
- Office Supplies demonstrate inelastic demand as workplace essentials
- Furniture shows moderate elasticity as a considered, durable purchase

### 7. Customer Lifetime Value and Churn
- Average CLV of $24,951 with an average customer lifetime of 40 months
- CLV trending upward from $24K in 2020 to $29K by Q1 2025
- Victoria records the highest churn rate at 57%, followed by
  Tasmania at 50% and WA at 46%
- Queensland maintains the lowest churn at 11%, providing a
  replicable engagement model
- Cohort analysis identifies Quarters 5 to 8 as the critical
  inflection point where loyalty erosion begins



## 💡 Key Insights

- Revenue is heavily concentrated in a small group of high-value
  clients and core product categories
- Seasonal demand is highly predictable, peaking in Q4 each year
  driven by corporate budget cycles
- Customer behaviour follows identifiable lifecycle patterns,
  particularly in Furniture and Technology (2 to 3 year purchase cycles)
- Major metropolitan cities underperform relative to smaller
  regional centres, suggesting localisation gaps
- Churn risk is geographically concentrated and addressable
  through targeted retention strategies



## 🚀 Strategic Recommendations

**Product Strategy**
Protect Paper as the margin anchor through strategic bundling with
complementary lower-margin items. Accelerate Storage and ergonomic
Furniture to capture post-pandemic workspace investment trends.
Review Machines and Copiers for phase-out or reduced inventory.

**Pricing Strategy**
Adopt flexible pricing for Technology products to respond to
high elasticity. Maintain stable premium positioning for Office
Supplies. Introduce tiered bundles combining high-volume,
low-margin items with high-margin, low-volume products.

**Customer Retention**
Replicate Queensland's engagement model (11% churn) in
Victoria and Tasmania through localised loyalty programs and
post-purchase touchpoints. Deploy predictive churn scoring
by Quarter 5 before loyalty erosion accelerates.

**Regional Expansion**
Invest in ACT and NT markets which show high growth
potential with low current penetration. Conduct city-level
segmentation in Sydney and Brisbane to close the
underperformance gap versus regional centres.

**Target Setting**
Recalibrate forecasting models for consistently
overperforming sub-groups including Phones, Storage, and
Chairs. Shift from static historical benchmarks to
dynamic, data-driven target setting.




## 📎 Project Value

This project demonstrates:

- End-to-end BI workflow from data cleaning through to
  strategic recommendations
- Application of RFM modelling and CLV analysis in a
  real B2B context
- Proficiency in Tableau dashboard design across
  multiple analytical dimensions
- Ability to synthesise complex multi-year data into
  clear, executive-level insights
- Strong understanding of Australian market dynamics
  and regional business behaviour



## 👤 Author

**Mark Le**
Aspiring Data Analyst / Business Analyst
Melbourne, Australia

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue)](https://www.linkedin.com/in/markle1304/)
