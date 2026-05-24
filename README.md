# FedEx Logistics Performance Analysis
### Exploratory Data Analysis | Python | Pandas | Seaborn | Plotly

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/18Cjp1zJsphiMHU8CzfBVVAzmrHi7ntr-?usp=sharing)

---

## Project Overview

This project performs an in-depth Exploratory Data Analysis (EDA) on FedEx supply chain logistics data covering pharmaceutical shipments across global medical supply chains. The goal is to identify patterns in delivery delays, freight costs, shipment modes, and vendor performance — and translate those findings into actionable business insights.

---

## Problem Statement

Shipment delays and high freight costs in pharmaceutical logistics directly affect the delivery of life-saving ARV medicines and medical supplies to patients in need. This analysis investigates:

- Which shipment modes and INCO terms lead to the most delays
- Which vendors and countries show the worst delivery performance
- How freight costs vary across shipment modes and weight
- What factors most influence on-time delivery

---

## Dataset

| Detail | Info |
|--------|------|
| File | SCMS_Delivery_History_Dataset.csv |
| Records | 10,000+ shipment entries |
| Features | 33 columns |
| Domain | Pharmaceutical supply chain logistics |

Key columns: Shipment Mode, Freight Cost (USD), Scheduled Delivery Date, Delivered to Client Date, Vendor INCO Term, Country, Weight (Kilograms), Product Group

---

## Tools & Technologies

| Tool | Purpose |
|------|---------|
| Python | Primary language |
| Pandas & NumPy | Data loading, cleaning, manipulation |
| Matplotlib & Seaborn | Static visualizations |
| Plotly | Interactive visualizations |
| Google Colab | Development environment |
| GitHub | Version control and project hosting |

---

## Project Structure

fedex-eda-capstone/
├── data/
│   └── SCMS_Delivery_History_Dataset.csv
├── notebooks/
│   ├── FedEx_EDA_Capstone.ipynb
│   └── README.md
└── README.md

---

## Notebook Structure

1. Project Summary and Business Objective
2. GitHub Link
3. Problem Statement
4. Data Loading and First View
5. Data Cleaning — null values, duplicates, type conversions
6. Understanding Variables
7. Univariate Analysis
8. Bivariate Analysis
9. Multivariate Analysis
10. 20 Visualizations with business interpretation
11. Business Questions and Answers
12. Conclusion and Recommendations

---

## Key Findings

- Air shipments cost significantly more than sea but show stronger on-time delivery rates
- Specific countries show consistently higher delay rates, pointing to route-level risk
- A small group of vendors account for a disproportionate share of late deliveries
- Freight cost and shipment weight show a moderate positive correlation
- Certain INCO terms are linked to better vendor delivery compliance

---

## How to Run

1. Click the Open in Colab badge above
2. Go to Runtime → Run All
3. All charts and outputs render inline — no setup needed

---

## Author

Vivek Kashinath Baviskar
