# Blinkit Sales & Outlet Performance Dashboard

An interactive Power BI dashboard analyzing sales, ratings, and outlet performance for **Blinkit — India's Last Minute App**, built to help stakeholders understand how sales and item visibility vary across outlet size, location tier, item type, and fat content category.

## 🔗 Live Preview
![Blinkit Dashboard](screenshot.png)
*(Add your dashboard screenshot to the repo and update the path above)*

## 📌 Project Overview
This dashboard consolidates outlet-level sales data into a single interactive report, letting users slice performance by **Outlet Size**, **Outlet Location (Tier)**, and **Item Type**. It answers questions like:
- Which outlet types and sizes drive the most sales?
- How does item fat content (Low Fat vs Regular) affect sales across outlet tiers?
- Which item categories contribute most to revenue?
- How has outlet establishment (store count/sales) trended from 2012–2022?
- How do Tier 1, 2, and 3 locations compare in sales contribution?

## 🎯 Business Objective
Retail and quick-commerce operators need visibility into outlet- and item-level performance to guide inventory allocation, outlet expansion, and category management decisions. This dashboard turns raw transactional data into an at-a-glance, filterable decision-support tool.

## 📊 Key Metrics (KPIs)
| Metric | Value |
|---|---|
| Total Sales | $1.20M |
| Average Sales | $141 |
| No. of Items | 8,523 |
| Average Rating | 3.9 |

## 🧩 Dashboard Features
- **Filter Panel** — slice by Outlet Size (High/Medium/Small), Outlet Location (Tier 1/2/3), and Item Type, with a one-click "Clear all slicers" reset
- **Tab navigation** — toggle the Item Type visual between Total Sales, Avg Sales, Avg Rating, and No. of Items
- **Fat Content Analysis** — donut chart (Low Fat 65% vs Regular 35%) and a breakdown by outlet tier
- **Item Type Breakdown** — horizontal bar chart ranking 16 item categories by sales (Fruits & Vegetables and Snack Foods lead at $0.18M each)
- **Outlet Establishment Trend** — line chart tracking sales by outlet opening year (2012–2022), highlighting a 2018 peak at $205K
- **Outlet Size & Location Distribution** — donut and bar charts showing sales share across Medium (42%), High (21%), and Small (37%) outlets, and Tier 1–3 locations
- **Outlet Type Summary Table** — Total Sales, Avg Sales, No. of Items, Avg Rating, and Item Visibility broken out by outlet type (Supermarket Type 1/2/3, Grocery Store)

## 🔍 Key Insights
- **Supermarket Type1** drives the majority of revenue at **$788K** total sales across 5,577 items — far outpacing the other three outlet types combined.
- **Low Fat items outsell Regular items** (65% vs 35% of total sales), a pattern that holds consistently across all three location tiers.
- **Fruits & Vegetables** and **Snack Foods** are the top-performing item categories, each contributing **$0.18M** in sales.
- **Tier 3 locations** generate the highest item volume (3.35K), followed by Tier 2 (2.79K) and Tier 1 (2.39K).
- Outlet establishment sales spiked sharply for outlets opened in **2018 ($205K)**, a clear outlier against a otherwise flat $128K–$133K range.
- Average rating is remarkably consistent at **3.9** across every outlet type, suggesting customer satisfaction isn't a differentiator of sales performance here.

## 🛠️ Tools & Skills Used
- **Power BI Desktop** — data modeling, DAX measures, interactive report design
- **DAX** — KPI cards, dynamic tab-switching measures, percentage-of-total calculations
- **Power Query** — data cleaning and transformation
- Data visualization best practices: slicers, bookmarks/tab navigation, conditional formatting on the summary table

## 👤 Author
**Vikram Kaushik**
[LinkedIn](https://linkedin.com/in/vikramkaushik007) · [GitHub](https://github.com/vikram-kaushik)
