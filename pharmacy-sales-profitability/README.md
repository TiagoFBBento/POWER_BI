# 📊 Pharmacy Sales & Profitability Analytics  
**ZoomCharts / Onyx Data Challenge**

---

## 🔗 Dashboard Link  
*https://app.powerbi.com/groups/me/reports/d8900818-4ecb-41ab-bedd-a41d295df22b/85b6072dc8a26c18c548?experience=power-bi*

---

## 🎯 Objective  
To analyze sales and profitability performance of a European pharmacy chain distributor, identifying key geographic, temporal, and product-level drivers of revenue, volume, and margin.

The report aims to support strategic decision-making by highlighting:
- Regional contributions to overall business results
- Performance differences across pharmacies
- Product-level profitability and volume patterns

---

## 📂 Dataset Overview  
The dataset represents **daily sales transactions** across multiple European countries.

### Fact Table
**FactSales**
- Revenue (€)
- Units Sold
- Cost (€)
- Margin (€)
- Promotion Flag
- DateKey
- PharmacyID
- ProductID

### Dimension Tables
**DimDate**
- Date
- Month
- Year
- YearMonth
- Quarter

**DimPharmacy**
- Country
- Region
- City
- Pharmacy Type (Urban / Suburban / Rural)
- Store Size

**DimProduct**
- Product Name
- Category
- Brand
- Pack Size
- Generic Flag

---

## 📏 Key DAX Measures
- Total Revenue (€)
- Total Units Sold
- Total Margin (€)
- Revenue MoM %
- Units Sold MoM %
- Margin MoM %
- Cost (€)

Measures are grouped by domain (Revenue, Units, Margin) for clarity and scalability.

---

## 🧭 Dashboard Structure

### 📝 Page 1: Business Performance Overview

#### KPIs
- **Revenue (€)** – total revenue with monthly sparkline
- **Units Sold** – total units sold with monthly sparkline
- **Margin (€)** – total margin with monthly sparkline

#### Insights
1. **Countries with the Highest Units Sold**
   - Identifies markets with the largest sales volume
   - Highlights demand distribution independent of pricing

2. **Countries and Regions Contributing Most to Revenue and Margin**
   - Comparison of absolute revenue and profitability
   - Drill-down from country to region

3. **Interactive Filters**
   - Year
   - Pharmacy Type
   - Product Name

This page provides an executive-level snapshot of overall business performance.

---

### 📝 Page 2: Time & Regional Performance

#### Insights
1. **Revenue, Units Sold, and Margin Over Time**
   - Monthly trends
   - Identification of seasonal patterns

2. **Country → Region → Pharmacy Analysis**
   - Performance comparison within regions
   - Identification of outperforming and underperforming pharmacies

3. **Pharmacy Type Performance**
   - Comparison between Urban, Suburban, and Rural pharmacies
   - Analysis of volume and profitability differences

This page focuses on **trend analysis and geographic performance consistency**.

---

### 📝 Page 3: Product & Promotion Analysis

#### Insights
1. **Top Product Categories and Brands**
   - By revenue
   - By margin

2. **Volume vs Margin Trade-Off**
   - High-volume, low-margin products
   - Low-volume, high-margin products

3. **Promoted vs Non-Promoted Sales**
   - Comparison of units sold and margin
   - Evaluation of promotion effectiveness

This page supports **product strategy and promotional decision-making**.

---

## 🗺️ Geographic Analysis
- Interactive geographic visuals reveal spatial patterns in sales and profitability
- Enables quick identification of strong and weak regions

---

## 🧠 Design & Methodology Notes
- Clear separation between overview, trend analysis, and product insights
- Minimal visual redundancy to reduce cognitive load
- Interactivity used only where it adds analytical value
- Layout designed for both executive and analytical audiences

---

## 📬 Author  
*(Name / LinkedIn link to be added)*
