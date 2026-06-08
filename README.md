<div align="center">

# 📊 Food Mart Retail — Power BI Analytics Dashboard

[![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com)
[![CSV](https://img.shields.io/badge/Data-CSV%20%2F%20Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)](https://microsoft.com/excel)
![Sales](https://img.shields.io/badge/Total%20Sales-1.76M-blue?style=for-the-badge)
![Transactions](https://img.shields.io/badge/Transactions-113K-orange?style=for-the-badge)
![Countries](https://img.shields.io/badge/Countries-USA%20%7C%20Canada%20%7C%20Mexico-green?style=for-the-badge)

**A 5-page interactive Power BI dashboard delivering end-to-end retail analytics for the Food Mart chain — covering sales KPIs, customer segmentation, product profitability, geographic distribution, and strategic business recommendations across 24 stores in 3 countries.**

[📊 View Dashboard (.pbix)](./Dashboards%20Food%20Mart%20Retail%20Analysis%20Project.pbix) · [📂 Data Folder](./data/) · [🐛 Report Bug](https://github.com/ahmedayman2825/vis/issues)

</div>

---

## 📌 Overview

<!-- Add a brief description of your project goals, context, or course here -->
<!-- e.g. "This dashboard was developed as part of the Data Visualization course at Alexandria University ..." -->
<!-- e.g. "The goal was to build a self-service BI tool that helps retail managers monitor KPIs at a glance, identify underperforming stores, and understand customer behavior — without needing to query raw data." -->

This project delivers a fully interactive **Power BI retail analytics solution** for **Food Mart** — a multi-national grocery chain operating across the **United States, Canada, and Mexico**.

Built on a star-schema data model with **6 relational tables** and over **113,000 transactions**, the dashboard enables business stakeholders to explore retail performance across time, geography, store type, product category, and customer demographics — all inside a single `.pbix` file with no external dependencies.

The dashboard concludes with a dedicated **Report page** surfacing written business insights and 13 actionable strategic recommendations derived directly from the data.

---

## 🖼️ Dashboard Pages

### 1️⃣ Main Figures — Executive KPI Overview
<img width="1487" height="833" alt="image" src="https://github.com/user-attachments/assets/60c98ebb-885b-45a4-a3a6-13f4da63077c" />

> **Key metrics at a glance:**
> - 💰 **$1.76M** Total Sales · **59.67%** Profit Margin · **$711.73K** Total Cost
> - 🔁 **8,289** Total Returns · **113K** Transactions · **111** Brands Traded
> - 📊 Top 10 Brands by transaction volume (Hermanos leads at 57K)
> - 👑 Top customers by purchase count (Ida Rodriguez #1 with 2,235)
> - 🥧 Member card breakdown: Bronze **56.1%** · Normal **23.1%** · Golden **12.4%** · Silver **8.4%**
> - 🌍 Sales region split: North West **48%** dominates all regions

---

### 2️⃣ Customer Insights
<img width="1489" height="835" alt="image" src="https://github.com/user-attachments/assets/6149a514-78f6-43c8-a5c9-3400ebe93291" />

> - 📍 **North West** leads regional sales at **$0.85M**, followed by Mexico Central ($0.33M) and South West ($0.32M)
> - 🎓 Education split: Partial High School **30.1%** · High School **29.6%** · Bachelors **25.5%** — majority are non-graduates
> - ⚖️ Gender is balanced across all education levels (Female ≈ Male in every bracket)
> - 📅 Customer activity peaks early in the year and **declines sharply toward December**
> - 👶 Treemap shows households with **1–2 children** account for the largest sales share
> - 🃏 Slicers: filter by **Yearly Income** and **Member Card** tier

---

### 3️⃣ Product Insights
<img width="1484" height="836" alt="image" src="https://github.com/user-attachments/assets/a3786118-d9d6-42dc-9458-a005ebe191c1" />

> - 📋 **Top 50 products** ranked by total sales — Carlson Head Cheese ($2,417), Better Chicken Soup ($2,292), and Big Time brands dominate
> - ♻️ **Recyclable products outperform non-recyclable** ones in total sales
> - 🥓 **High-fat products** outsell low-fat products (~0.4M vs ~0.25M)
> - 🗺️ **North West** generates the most profit ($0.22M) and sales ($0.36M) by region
> - 📈 Sales and profit trend upward from Jan 1997 through mid-1998
> - 📦 **WA state** has the highest return volume, followed by CA and OR
> - 🔘 Slicers: filter by **Year** (1997 / 1998) and **Recyclable** status

---

### 4️⃣ Geography
<img width="1486" height="854" alt="image" src="https://github.com/user-attachments/assets/6e447155-5e32-4f6a-8dcc-c8442bb2f207" />

> - 🗺️ **Store Distribution Map** — 24 stores plotted across North America (USA 🟠 · Canada 🔵 · Mexico 🔵)
> - 📈 **Top 3 Regions Sales Trend** (Jan 1997 – Jul 1998): North West consistently leads, followed by Mexico Central and South West
> - 📊 **Region vs Returns**: North West has the highest return volume — a quality/policy concern
> - 🏬 **Stores by Region**: North West has the most stores, followed by Mexico Central
> - 🛒 **Top 5 Products per region**: Hermanos Green Pepper, Hilltop Mint Mouthwash, Carlson Head Cheese, Great Pumpernickel Bread, Fabulous Strawberry Drink

---

### 5️⃣ Store Analysis Report — Summary & Recommendations
<img width="1483" height="836" alt="image" src="https://github.com/user-attachments/assets/bbebe717-35df-432f-913a-f64c0a2b6c1a" />

> **Summary highlights:**
> - $1.76M total sales · 59.67% profit margin · 113K transactions across 111 brands
> - 8,289 returns signal need for quality monitoring
> - North West leads regional sales; customer activity declines toward year-end
> - Recyclable, high-fat products outperform — sustainability matters
>
> **13 Business Recommendations include:**
> - Prioritize **North West** for expansion
> - Launch **Q4 seasonal campaigns** to counter year-end engagement drop
> - Target **Bronze members** with loyalty upgrade offers
> - Design **family-oriented bundles** for 1–2 children households
> - Promote **recyclable packaging** as a competitive advantage
> - Investigate **high return rates in WA** state

---

## ✨ Features

| Feature | Description |
|---|---|
| **6 KPI Cards** | Total Sales, Profit %, Total Cost, Returns, Transaction Count, Brands Traded |
| **Star Schema Model** | 6 tables linked via `product_id`, `customer_id`, `store_id`, `region_id` |
| **Customer Segmentation** | Income brackets, member card tier, gender, education, children at home, marital status |
| **Product Profitability** | Margin from retail price vs cost; recyclable & low-fat product filters; top-50 ranking |
| **Geographic Analysis** | Interactive map + regional trend lines + return rate by region + store count by region |
| **Time Intelligence** | Monthly customer trend, year-over-year sales & profit, transaction timeline |
| **Returns Analysis** | 8,289 returns tracked by product, state (WA leads), and region |
| **Business Report Page** | Written summary + 13 strategic recommendations auto-derived from dashboard insights |
| **Cross-page Navigation** | Sidebar navigation across all 5 pages |
| **Interactive Slicers** | Year, Recyclable, Yearly Income, Member Card — all cross-filter every visual |

---

## 🗂️ Data Model

```
                   ┌─────────────┐
                   │   Region    │ (109 rows)
                   │  region_id  │
                   └──────┬──────┘
                          │
┌──────────────┐   ┌──────┴──────┐   ┌──────────────┐
│  Customers   │   │   Stores    │   │   Products   │
│ 10,281 rows  ├───┤  24 rows    ├───┤  1,560 rows  │
│ customer_id  │   │  store_id   │   │  product_id  │
└──────┬───────┘   └──────┬──────┘   └──────┬───────┘
       │                  │                  │
       └──────────┬───────┘                  │
                  ▼                          │
           ┌─────────────┐           ┌───────┴─────┐
           │    Sales    │           │   Returns   │
           │ 269,722 rows│           │  7,087 rows │
           └─────────────┘           └─────────────┘
```

| Table | Rows | Key Fields |
|---|---|---|
| `Sales.csv` | 269,722 | `transaction_date`, `product_id`, `customer_id`, `store_id`, `quantity` |
| `Customers.csv` | 10,281 | `yearly_income`, `member_card`, `gender`, `education`, `num_children_at_home` |
| `Products.csv` | 1,560 | `product_retail_price`, `product_cost`, `recyclable`, `low_fat` |
| `Stores.csv` | 24 | `store_type`, `store_country`, `total_sqft`, `grocery_sqft` |
| `Region.csv` | 109 | `sales_district`, `sales_region` |
| `Returns.csv` | 7,087 | `return_date`, `product_id`, `store_id`, `quantity` |

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| **Power BI Desktop** | Dashboard design, data modeling, DAX measures, all visualizations |
| **Power Query (M)** | Data transformation, type casting, column cleanup on import |
| **DAX** | Measures: Total Sales, Profit %, Return Rate, transaction counts, time intelligence |
| **CSV / Excel** | Source data format for all 6 relational tables |

---

## 🚀 Getting Started

### Prerequisites

- **Power BI Desktop** (free) — [Download here](https://powerbi.microsoft.com/desktop/)
- Windows OS (Power BI Desktop is Windows-only)

> **Mac users:** Use [Power BI Service](https://app.powerbi.com) via browser, or run Power BI Desktop in a Windows VM / Parallels.

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/ahmedayman2825/vis.git
cd vis
```

### Open the Dashboard

1. Launch **Power BI Desktop**
2. `File → Open report` → select `Dashboards Food Mart Retail Analysis Project.pbix`
3. If prompted about data source paths → `Transform Data → Data Source Settings` → update path to your local `/data/` folder
4. Click **Refresh** to reload all tables

---

## 📁 Repository Structure

```
vis/
│
├── Dashboards Food Mart Retail Analysis Project.pbix   # Main Power BI file (5 pages)
│
├── data/
│   ├── Sales.csv          # 269,722 transactions (central fact table)
│   ├── Customers.csv      # 10,281 customer profiles
│   ├── Products.csv       # 1,560 SKUs with cost & retail price
│   ├── Stores.csv         # 24 stores across USA, Canada, Mexico
│   ├── Region.csv         # 109 sales districts and regions
│   └── Returns.csv        # 7,087 return records
└── README.md
```

---

## 💡 Key Business Insights

| # | Insight |
|---|---|
| 🥇 | **North West** generates 48% of all regional sales and leads in profit — top expansion priority |
| 📅 | Customer activity **peaks in early months** and drops sharply toward year-end → seasonal campaigns needed in Q4 |
| 🃏 | **Bronze members** are the largest segment (56.1%) — loyalty upgrade programs can unlock revenue |
| ♻️ | **Recyclable products** outperform non-recyclable — sustainability is a market differentiator |
| ⚠️ | **WA state** has the highest return rate — requires quality review and after-sales improvement |
| 👨‍👩‍👦 | Households with **1–2 children** are the largest buying group — family bundles have strong potential |

---

## 🔭 Future Improvements

- [ ] Publish to **Power BI Service** and add a live embedded link to this README
- [ ] Add a **Forecasting page** using Power BI's built-in time-series forecasting for 1997–1998 trends
- [ ] Implement **RFM segmentation** (Recency, Frequency, Monetary) as DAX-calculated tiers
- [ ] Build a proper **DAX Date Table** for reliable YTD, MoM, and YoY time intelligence
- [ ] Add a **What-If parameter** to simulate margin impact of pricing changes
- [ ] Expand returns analysis with a dedicated **Returns deep-dive page** by product category

---

## 👥 Contributors

**Team 1** — Alexandria University

 **Ahmed Ayman**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/eng-ahmed-ayman/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/ahmedayman2825)

**Ahmed Tawfik**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ah-mo-tawfik/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/tAwFiK2005)

**Ashraf Khamis**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ashraf-k-eesa-b8b8802b4)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/ashrafeesa)

**Ahmed Abdelwahab**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ahmed-abdalwahab/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/ahmedabdalwahab)

**Ahmed Emad**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ahmed-zamel09/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/AhmedZamel09)

---

<div align="center">
  <sub>If you found this project useful, consider giving it a ⭐</sub>
</div>
