# Zen EliteStride Maison - Power BI Sales Analysis Project  

**Executive summary**
---
![Zen EliteStride Maison](https://github.com/Tusneld/Zen-EliteStride-Maison_Power-BI/blob/2a767f5749ea78db08bddbe4b33c9fe570311698/Executive%20sumaary.PNG)
---

## 📋 Project Overview

**Zen EliteStride Maison** is a Power BI-based sales analysis project that transforms raw, disconnected Excel shoe sales data into a powerful, interactive business intelligence dashboard. The project delivers a centralized view of revenue performance, profit margins, customer behavior, and product trends - enabling data-driven decision making for the business.

## 🏢 Business Problem Statement

Stakeholders within Zen EliteStride Maison struggle to derive actionable insights from raw, disconnected sales data. Without a centralized view, the business cannot effectively track revenue performance, profit margins, or customer behavior, leading to significant gaps in data-driven decision making.

## 🎯 Objective & Goal

The primary objective is to transform raw Excel-based shoe sales data into an **interactive Power BI dashboard** that provides:
- A holistic overview of business health
- Deep insights into product and brand performance
- Clear visibility into customer payment behaviors and trends
- Actionable recommendations to guide future business strategy


## 🛠️ Tech Stack

- **Power BI Desktop** (latest version)
- **Excel** (source data)
- **Power Query** (data transformation & cleaning)
- **DAX** (calculated measures)
- **Data Modeling** (relationships between tables)
- **Visualization Tools**: Line charts, bar charts, treemaps, slicers, and KPI cards

## 📋 Step Taken

1. **Data Integration** - Imported all disparate Excel sheets into a unified data model.
2. **Data Cleaning** - Used Power Query to remove empty rows, standardize text casing, and trim whitespace.
3. **Data Modeling** - Created a many-to-one relationship between the **Shoe Sales** (fact table) and **Price** (dimension table) based on the **Product** column.
4. **DAX Development** - Built calculated measures using `SUMX` and the `RELATED` function for accurate cross-table calculations.
5. **Dashboard Creation** - Designed three interactive tabs: Executive Overview, Product/Brand Deep Dive, and Customer Behavior.
6. **Testing & Validation** - Verified all relationships and metrics work correctly across the dataset.

## 📊 Key Metrics & Insights

- **Total Revenue**: Calculated by iterating through sales quantities and multiplying by corresponding prices using `SUMX`
- **Total Profit**: Measures financial gain after accounting for production costs
- **Sales Trends**: Visualized through line charts over time and broken down by geography and product type

## 📈 Lessons Learned

- **Relationship Importance**: Defining proper relationships between tables is critical — without them, visuals fail to aggregate correctly across disconnected data sources
- **DAX Precision**: `SUMX` enables row-level iteration, which is essential for accurate multi-table calculations (standard SUM is insufficient)
- **Clarity Over Complexity**: The most effective dashboards focus on clear business questions and simplicity rather than overwhelming design

## 🚀 Instructions for Use

1. Ensure you have the **latest version of Power BI Desktop** installed
2. Load the **Zen Elite Stride** dataset using **Get Data > Excel workbook** connector
3. Verify that the relationship between the **Shoe Sales** and **Price** tables is active in the **Model** view
4. Explore the three main dashboard tabs:
   - Executive Overview
   - Product/Brand Deep Dive
   - Customer Behavior

## Key Insights

### 1. Overall Performance
The business generated **$355,048** in total revenue and **$162,335** in total profit across **4,012 units sold**, for a **45.7% profit margin** and an **average order value of $710.10**.

### 2. Revenue and Profit Over Time
Monthly performance holds fairly steady from January through May (roughly $40K–$45K per month), then jumps sharply in **June** — **$70,771 in revenue** and **$32,123 in profit**, nearly 60% higher than surrounding months — before dropping off in **August** ($16,041 in revenue, based on a partial month of data). June stands out as a clear seasonal peak.

### 3. Products Driving Sales
By revenue, the top performers are:
- **Canvas** — $63,488
- **Oxford** — $58,905
- **Brogues** — $58,576

### 4. Products Driving Profitability
Margin tells a different story than revenue alone:
- **Derby** has the highest profit margin at **56.3%**, despite the lowest revenue ($16,704) of any product.
- **Boots** (48.7%) and **Loafers** (48.1%) also outperform Canvas (43.8%) on margin.

Canvas is the clear volume and revenue driver, while Derby and Boots are the efficiency drivers — strong candidates for margin-focused promotion or bundling.

### 5. Best-Performing Categories and Brands
- **Formal** dominates the category mix at **$179,935 (50.7% of total revenue)** — more than Casual, Open, and Utility combined.
- **Clarks** leads all brands decisively at **$123,543**, ahead of Zara ($94,797), Nike ($54,029), Steve Madden ($43,855), and Timberland ($38,824).

### 6. Country Contribution
Revenue is spread fairly evenly across 14 countries, with no single dominant market:
- **USA** — $39,127
- **UK** — $32,871
- **Ghana** — $32,026
- **Zimbabwe** — $30,124

The gap between the top market (USA) and the lowest (Albania, $14,592) is less than 3x, pointing to a genuinely diversified international customer base rather than reliance on one region.

### 7. Purchasing Patterns by Payment Method
- **Card** — $99,257 (1,108 units) — most-used payment method
- **Bank Transfer** — $94,100 (1,043 units)
- **Cash** — $93,540 (1,049 units)
- **Mobile Money** — $68,151 (812 units) — noticeably behind the other three

Card, Bank Transfer, and Cash are all within a few percentage points of each other, while Mobile Money trails, suggesting lower adoption or a market/demographic mismatch worth investigating.

### 8. Recommended Actions for Management
- **Double down on Formal and Clarks** — the strongest category and brand combination, with room to expand the lineup.
- **Promote Derby and Boots alongside Canvas** — pairing high-margin, lower-volume products with the top revenue driver (e.g., bundling) could lift overall profit without needing new demand.
- **Plan inventory and staffing around the June peak** — and investigate whether the July–August drop is seasonal or partly a data artifact from the partial month.
- **Investigate Mobile Money's lower uptake** — a targeted incentive (cashback, small discount) could help close the gap with Card, Bank Transfer, and Cash.
- **Maintain the diversified country base** rather than over-concentrating marketing spend in the top 2–3 markets, since the spread across countries is a strength.
---

## 👤 Author

**Tusnelde Endjala**  
Power BI & Business Intelligence Portfolio Project

**Last Updated**: September 2026
