# ecommerce-sales-analysis
Exploratory data analysis on Superstore retail dataset using Python, Pandas &amp; Plotly. Uncovering sales trends, profit drivers &amp; customer segments across 9,994 transactions.
# 🛒 E-Commerce Sales Analysis

> Exploratory Data Analysis on the Superstore retail dataset — uncovering sales trends, profit drivers, and customer behavior using Python and Plotly.

---

## 📌 Project Overview

This project performs a comprehensive analysis of a US-based e-commerce superstore's transactional data spanning **4 years (2014–2017)** with **9,994 records**. The goal is to extract actionable business insights around sales performance, profitability, and customer segmentation.

---

## 📊 Key Findings

| Insight | Detail |
|---|---|
| 💰 Total Sales | $2.3 Million |
| 📈 Total Profit | $286,397 |
| 📉 Profit Margin | 12.5% |
| 🏆 Best Month | November ($352K) |
| ⚠️ Worst Sub-Category | Tables (−$17,725 profit) |
| 🌍 Top Region | West ($725K) |

### Highlights
- **Technology** leads in both sales ($836K) and profit ($145K)
- **Furniture** has high sales ($742K) but only 2.5% profit margin — a pricing concern
- **Discounts above 20%** result in negative average profit per transaction
- **Q4 (Oct–Dec)** is the strongest sales quarter — ideal for marketing campaigns
- **Consumer segment** contributes 50.6% of total revenue
- **Tables, Bookcases, and Supplies** are loss-making sub-categories

---

## 🗂️ Project Structure

```
ecommerce-sales-analysis/
│
├── E_commerce_project.ipynb        # Main analysis notebook
├── Sample_Superstore.csv           # Dataset (9,994 records, 21 columns)
├── ECommerce_Sales_Presentation.pptx  # Project presentation deck
├── requirements.txt                # Python dependencies
└── README.md                       # Project documentation
```

---

## 🔍 Analysis Performed

1. **Monthly Sales Analysis** — Trend across 12 months, peak/low identification
2. **Sales by Category** — Technology vs Furniture vs Office Supplies
3. **Sales by Sub-Category** — 17 sub-categories ranked by revenue
4. **Monthly Profit Analysis** — Profit trends across the year
5. **Profit by Category & Sub-Category** — Winners and loss-makers identified
6. **Customer Segment Analysis** — Consumer, Corporate, Home Office breakdown
7. **Sales-to-Profit Ratio** — Efficiency metric per segment
8. **Discount Impact Analysis** — How discount levels affect profitability
9. **Regional Sales Analysis** — East, West, Central, South performance

---

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-2.0-lightblue?logo=pandas)
![Plotly](https://img.shields.io/badge/Plotly-5.15-purple?logo=plotly)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)

- **Python** — Core programming language
- **Pandas** — Data manipulation and aggregation
- **Plotly Express & Graph Objects** — Interactive visualizations
- **Jupyter Notebook** — Analysis environment

---

## 🚀 How to Run

**1. Clone the repository**
```bash
git clone https://github.com/YOUR_USERNAME/ecommerce-sales-analysis.git
cd ecommerce-sales-analysis
```

**2. Install dependencies**
```bash
pip install -r requirements.txt
```

**3. Launch the notebook**
```bash
jupyter notebook E_commerce_project.ipynb
```

---

## 📦 Dataset

**Source:** Superstore Sales Dataset (commonly used for data analysis practice)

| Feature | Detail |
|---|---|
| Records | 9,994 rows |
| Columns | 21 features |
| Time Period | 2014 – 2017 |
| Geography | United States |
| Categories | Furniture, Office Supplies, Technology |
| Regions | East, West, Central, South |

**Key Columns:** Order Date, Ship Date, Ship Mode, Customer Segment, Region, Category, Sub-Category, Sales, Quantity, Discount, Profit

---

## 💡 Business Recommendations

1. **Cap discounts at 20%** — any higher leads to guaranteed losses
2. **Audit Furniture pricing** — especially Tables (−$17.7K loss)
3. **Double down on Technology** — highest ROI category
4. **Prioritize Q4 marketing** — November and December are peak months
5. **Loyalty programs for Consumer segment** — they drive 50% of sales

---

## 👤 Author

**Abhinna_Singh — Data Analyst  
📍 Mirzapur, Uttar Pradesh, India  
🔗 [GitHub Profile](https://github.com/abhinna-singh)
