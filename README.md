# 📊 Amazon Sales Analysis Dashboard

A comprehensive, interactive data visualization tool designed to analyze and explore Amazon product sales performance—focusing on revenue trends, category performance, seasonal patterns, and customer satisfaction metrics across the entire fiscal year.

---

## 🎯 Short Description

The Amazon Sales Analysis Dashboard is a data-driven Power BI report built to help stakeholders explore year-to-date sales performance across multiple product categories, identify top-performing items, and understand customer feedback patterns. This dashboard is designed for sales managers, business analysts, marketing strategists, and senior leadership who need actionable insights to optimize inventory, pricing, and promotional strategies.

---
![Amazon Sales Analysis](https://github.com/chandradeep21003-afk/Amozon-Sales-Analysis/blob/main/Amozon%20Sales%20Analysis.png)
## 🛠️ Tech Stack

The dashboard was built using the following tools and technologies:

• **📊 Power BI Desktop** – Main data visualization and reporting platform for interactive dashboard creation.

• **📂 Power Query** – Data transformation and ETL layer for cleaning, reshaping, and preparing sales and customer data.

• **🧠 DAX (Data Analysis Expressions)** – Advanced calculations for YTD/QTD metrics, running totals, market share percentages, and dynamic KPI measures.

• **📋 Data Modeling** – Relationships established across product, sales, and customer review tables to enable cross-filtering and multi-dimensional analysis.

• **📁 File Format** – .pbix for development and interactive reports; .xlsx for source data repositories.

---

## 📁 Data Source

**Source:** Amazon product sales database with integrated customer feedback system.

The dataset encompasses comprehensive sales and product information from a full calendar year, including:

- **Product Catalog:** Product categories, SKUs, names, and pricing information across 6+ product lines.

- **Sales Transactions:** Daily transaction records with order dates, quantity sold, and revenue generated; aggregated into weekly and monthly summaries.

- **Customer Reviews & Ratings:** Review counts, customer ratings, and sentiment metrics tied to individual products and categories.

- **Temporal Aggregations:** Year-to-date (YTD), quarter-to-date (QTD), and month-over-month comparative data for trend analysis.

**Data Scope:** Full fiscal year analysis spanning January through December with daily transaction-level granularity.

---

## ✨ Features & Highlights

### 🔴 Business Problem

E-commerce platforms generate massive volumes of sales data daily, yet sales teams and business leaders often struggle to answer critical questions quickly:

- Which product categories drive the most revenue and market share?
- How do sales trends fluctuate across seasons and quarters?
- Which individual products are our top revenue generators?
- How engaged are customers with our products (based on reviews)?
- What patterns emerge in weekly vs. monthly performance?

Without a centralized, visual analytics tool, stakeholders rely on static reports and manual data analysis, resulting in delayed insights and missed opportunities for optimization.

---

### 🎯 Goal of the Dashboard

To deliver an interactive, multi-dimensional analytical tool that:

- Enables real-time exploration of sales performance across categories, products, and time periods.
- Supports strategic decisions on inventory allocation, marketing focus, and promotional campaigns.
- Uncovers seasonal trends, growth patterns, and emerging opportunities through visual storytelling.
- Provides stakeholders at all levels with self-service analytics capabilities for faster decision-making.

---

### 📊 Walkthrough of Key Visuals

**Key Performance Indicators (Top Section)**

Five primary metrics displayed as headline cards:

- **YTD Sales:** $2.2M — Total year-to-date revenue across all categories and products.
- **QTD Sales:** $811.09K — Current quarter-to-date performance for tracking progress toward quarterly goals.
- **YTD Products Sold:** 27,750 Units — Volume indicator showing product movement and customer demand.
- **YTD Reviews:** 19.42M — Engagement metric reflecting customer interaction and product visibility.

---

**Sales by Month (Line Chart)**

A monthly trend visualization showing sales progression from January through December.

- **Insight:** Clear seasonal pattern with growth trajectory peaking in Q4 (October-December).
- **Use Case:** Helps identify peak selling periods for inventory planning and staffing decisions.
- **Action:** Allocate additional inventory and marketing budget toward Q4 to capitalize on peak demand.

---

**Sales by Week (Column Chart)**

A weekly breakdown of sales performance across the entire year.

- **Insight:** Week-over-week consistency with identifiable spikes indicating promotional impact or demand surges.
- **Use Case:** Enables short-term performance monitoring and quick identification of underperforming weeks.
- **Action:** Investigate weeks with lower performance to identify external factors (stockouts, competition, etc.).

---

**Sales by Product Category (Heat Map / Table)**

A detailed table ranking all product categories by revenue performance.

| Category | YTD Sales | Market Share |
|----------|-----------|--------------|
| Men Shoes | $9.40M | 43.18% |
| Camera | $4.93M | 22.62% |
| Men Clothes | $3.58M | 16.42% |
| Car Accessories | $2.37M | 10.90% |
| Toys | $1.11M | 5.09% |
| Mobile & Accessories | $39.18K | 1.80% |

- **Insight:** Men Shoes dominate with nearly half of all sales; concentrated revenue risk in top 2 categories.
- **Use Case:** Identify which categories merit increased investment vs. which need growth initiatives.
- **Action:** Expand Men Shoes inventory; develop strategies to grow underperforming categories.

---

**Top 5 Products by YTD Sales (Bar Chart)**

A horizontal bar chart highlighting the highest revenue-generating individual products.

- Nikon Wireless Camera: $33.6K
- Atomos Ninja Series: $28.4K
- Solid Gear Pro: $26.9K
- Canal Toys Deluxe: $21.6K
- Vince Campus Collection: $19.4K

- **Insight:** Identifies blockbuster products driving disproportionate revenue.
- **Use Case:** Focus marketing and customer service excellence on these key revenue drivers.
- **Action:** Ensure continuous stock availability; negotiate better supplier terms for volume discounts.

---

**Top 5 Products by YTD Reviews (Bar Chart)**

A visualization of the most-reviewed (and thus most customer-engaged) products.

- SanDisk 1TB Storage: 402.83K reviews
- SanDisk 1TB Pro: 337.40K reviews
- SanDisk 4TB Ultra: 227.96K reviews
- JETech Screen Guard: 155.71K reviews
- WOLVERI Protection Case: 139.35K reviews

- **Insight:** High review volume indicates strong customer engagement and product visibility.
- **Use Case:** Identify products with strong customer endorsement for marketing leverage.
- **Action:** Feature high-review products prominently; use customer testimonials in campaigns.

---

### 💼 Business Impact & Insights

**Revenue Optimization**

The dashboard reveals that Men Shoes alone account for 43% of revenue. By allocating targeted marketing and inventory investment to this category, the business can maximize short-term profitability while developing strategies to grow underpenetrated categories.

**Seasonal Planning & Forecasting**

Clear Q4 peaks enable more accurate demand forecasting, allowing supply chain teams to prepare for seasonal surges without overstocking during low-demand periods.

**Product Portfolio Management**

Top-5 product analysis identifies key revenue drivers and customer favorites, guiding decisions on:
- Which SKUs to prioritize for restocking.
- Which products to feature in promotional campaigns.
- Which underperformers may need bundling or discontinuation strategies.

**Customer Engagement Metrics**

The 19.42M reviews metric demonstrates strong customer engagement. High-review products serve as proof points for marketing campaigns, while low-review items may benefit from quality improvements or repositioning.

**Competitive Positioning**

Diversified revenue across multiple categories (despite top-category dominance) suggests a balanced portfolio less vulnerable to single-category disruption. The breadth enables cross-selling and bundling opportunities.

**Data-Driven Decision Making**

By making sales data accessible through an intuitive visual interface, stakeholders can make faster, more confident decisions—reducing time spent in manual analysis and increasing strategic focus.



## 📋 Dashboard Features

### Visualizations Included

✓ **YTD Sales by Month** (Line Chart)
- Monthly trend analysis for seasonal pattern identification
- Growth trajectory visualization

✓ **YTD Sales by Week** (Column Chart)
- Weekly performance granularity
- Short-term fluctuation insights
- Promotional impact identification

✓ **Sales by Product Category** (Heat Map/Table)
- Category-wise revenue breakdown
- Market share distribution
- YTD vs QTD comparative analysis

✓ **Top 5 Products by YTD Sales** (Bar Chart)
- Revenue-generating product identification
- Performance benchmarking

✓ **Top 5 Products by YTD Reviews** (Bar Chart)
- Customer satisfaction indicators
- Product popularity metrics
