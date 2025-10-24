# 📊 Excel Sales Dashboard — Data Cleaning, Analysis & Visualization

> **An interactive Excel dashboard displaying category-wise, product-wise, monthly, and regional sales performance — built from cleaned and transformed raw sales data.**

---

## 🧾 Overview

This project demonstrates the **complete lifecycle of Excel-based data analytics** — from raw data cleansing and transformation to dynamic visualization through **pivot tables**, **pivot charts**, and **interactive slicers**.

The dashboard provides deep insights into:
- 🏷️ **Category-wise Sales**
- 📦 **Product-wise Performance**
- 🗓️ **Monthly Sales Trend**
- 🌍 **Region-wise Revenue Distribution**

and enables users to dynamically slice the entire report **by selected month(s)** using **Excel slicers**.

---

## 🎯 Project Objectives

✅ Clean and standardize large sales dataset (10,000+ records)  
✅ Handle missing, duplicate, and inconsistent entries  
✅ Build pivot tables for analytical summaries  
✅ Create interactive dashboard visuals linked with slicers  
✅ Enable month-based dynamic filtering and analysis  

---

## 🧰 Tools & Features Used

| Tool / Feature | Purpose |
|----------------|----------|
| **Microsoft Excel** | Primary platform for data processing and dashboard creation |
| **Power Query** | Automated data cleaning and transformation |
| **Pivot Tables** | Data summarization by category, region, and month |
| **Pivot Charts** | Visualization of KPIs and performance trends |
| **Slicers** | Month-based filtering for interactivity |
| **Conditional Formatting** | Highlighting top/bottom performers |
| **Formulas Used** | `TRIM()`, `PROPER()`, `IFNULL()`, `TEXT()`, `ROUND()` |

---

## 🧹 Data Cleansing & Formatting Process

### 1️⃣ Raw Data Preparation
- Imported sales transaction dataset into Excel  
- Identified **null**, **duplicate**, and **inconsistent** records  

### 2️⃣ Cleaning Steps
- Removed extra spaces using:  
  ```excel
  =TRIM(@FieldName)
Replaced empty numeric fields with 0

Removed duplicates via Data → Remove Duplicates

Verified correct date and currency formats

📊 Pivot Table Development
Created multiple pivot tables to analyze key performance areas:

Pivot Type	Description
Category-wise Sales	Total sales by product category
Product-wise Sales	Comparison of top-selling and low-performing products
Monthly Sales Trend	Aggregated monthly revenue trend (line chart)
Region-wise Sales	Revenue breakdown across all operating regions

Each pivot table serves as the data source for one or more charts in the dashboard.

📈 Dashboard Design
🪄 Layout
Dashboard sheet consolidates 4 pivot charts:

📦 Product-wise Sales

🏷️ Category-wise Sales

🗓️ Monthly Sales Trend (Line Chart)

🌍 Region-wise Sales (Bar/Map Chart)

🎛️ Interactivity
Added Slicer for Month — filters all pivot charts simultaneously

Linked slicer to all related pivot tables using:

PivotTable Analyze → Filter Connections → Select All Charts
