# Power BI Sales Analysis Project  
**Zen EliteStride Maison**

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

## 💡 Recommendations

- Regularly update the underlying data source to keep all insights current
- Use the dashboard to identify low-performing products and negotiate better costs with suppliers

---

## 👤 Author

**Tusnelde Endjala**  
Power BI & Business Intelligence Portfolio Project

**Last Updated**: September 2026
