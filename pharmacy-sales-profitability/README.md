# Pharmacy Sales & Profitability Analytics

This project is part of my **data analytics portfolio** and was developed using **Power BI** in response to a *Pharmacy Sales & Profitability Analytics Data Challenge*.

---

## 🧩 Stakeholder Questions

- How do **revenue, units sold, and margin** change over time, and are there clear seasonal patterns?
- Which **countries and regions** contribute the most to total revenue and margin?
- How does performance vary when drilling down from **country → region → pharmacy**?
- Which pharmacies **outperform or underperform** compared to others in the same region?
- How do **Urban, Suburban, and Rural** pharmacies differ in sales volume and profitability?
- Which **product categories and brands** generate the most revenue, and which generate the most margin?
- Are there products with **high sales volume but low profitability**, or **low volume but high profitability**?
- How do **promoted sales** compare to **non-promoted sales** in terms of volume and margin?
- How does **regional performance** contribute to overall business results?
- Are there visible **geographic patterns** in sales or profitability?

---

## 🗂️ Data Overview
  
The dataset includes information about:

- Date of sale
- Pharmacy and geographic location
- Pharmacy type (Urban, Suburban, Rural)
- Product, category, and brand
- Revenue, units sold, and margin

The data model follows a **star schema**, which is a standard and efficient structure for analytical reporting.

<div align="center">
  <img 
    src="https://github.com/user-attachments/assets/faf99928-f4f3-4cda-997a-8e597d5fe197" 
    alt="Power BI Data Model - Star Schema"
    width="500"
  />
  
  <br/>
  <sub><em>Power BI Data Model – Star Schema</em></sub>
</div>


---

## 🔑 Key Metrics Explained

The report focuses on a small set of core business metrics designed to be intuitive, comparable, and decision-oriented:

- **Revenue (€)**  
  Represents sales scale and overall market size.

- **Units Sold**  
  Represents demand and sales volume.

- **Margin (€ and %)**  
  Represents profitability:
  - **Margin (€)** shows total profit contribution.
  - **Margin (%)** measures operational efficiency, enabling fair comparisons between markets of different sizes.

- **MoM and YoY (%)**  
  Represent time intelligence metrics calculated using a dedicated date dimension, following best practices in analytical data modeling.

> Instead of using a generic *profit* metric, margin is intentionally used to clearly separate **scale** (revenue) from **efficiency** (margin %), which is critical for meaningful comparisons across countries, regions, and pharmacies.

All metrics used in the report are implemented as **custom DAX measures**, ensuring consistency across dashboards and drill-down levels.

---

## 🧭 Report Structure

### 🟦 Dashboard 1 - Business Performance Overview

<img width="800" height="800" alt="image" src="https://github.com/user-attachments/assets/87196963-35cf-4244-8306-35e60abbaf96" />

### 🎯 Purpose
Provide an executive-level snapshot of overall business performance.

### 📊 What it shows
- **Total revenue, units sold, and margin**
- **Performance trends over time**
- **Comparison between countries and regions**
- **Identification of high-volume vs high-profitability markets**
- **Year-over-year comparison (2024 vs 2025)**

### 🔍 Key Insights
- The business shows a stable upward trend in revenue, units sold, and margin over time, with no major structural downturns.
- Germany, France, and Italy lead in units sold, indicating the highest demand concentration across markets.
- Revenue and margin contribution is not proportional to sales volume, as some lower-volume countries generate relatively higher margins (e.g. Poland vs Austria in 2025).
- This confirms that sales scale alone does not guarantee profitability, reinforcing the need to evaluate volume and margin together.
- The 2024 vs 2025 comparison helps validate whether growth is structural rather than driven by short-term effects.

---

### 🟨 Dashboard 2 - Product & Category Performance

<img width="800" height="800" alt="image" src="https://github.com/user-attachments/assets/f32db3b6-d305-49ba-b4b1-75d69f45bb2e" />

### 🎯 Purpose
Understand how product categories, brands, and individual products drive revenue and profitability.

### 📊 What it shows
- 💰 Revenue and margin by product category  
- 📈 Identification of the most profitable categories  
- 🔍 Product-level analysis combining:
  - Units Sold (sales volume)
  - Margin % (profitability)
- 🧭 Scatter plot highlighting volume vs profitability trade-offs  
- 🔽 Drill-down from **Category → Brand → Product**

### 🔍 Key Insights
- Prescription and OTC categories generate the highest absolute revenue, forming the volume backbone of the business.
- Wellness and Personal Care stand out as the most profitable categories in terms of margin percentage, despite lower sales volumes.
- The volume vs profitability analysis confirms that higher sales volume does not necessarily translate into higher margin.
- Several products outperform expected margins for their sales volume, indicating strong pricing or cost control practices.
- High-volume, low-margin products represent clear candidates for pricing, promotion, or cost optimization reviews.

### 🟩 Dashboard 3 - Pharmacy & Regional Deep Dive

<img width="800" height="800" alt="image" src="https://github.com/user-attachments/assets/827ebc4e-0405-4ef3-acc0-b8e65260550d" />

### 🎯 Purpose
Analyze performance at a geographic and operational level, from country down to individual pharmacies.

### 📊 What it shows
- 🌍 Revenue and margin by country, region, and pharmacy  
- 📉 Performance variation within the same country  
- 🏙️ Comparison across **Urban, Suburban, and Rural** pharmacy types  
- 🗺️ Geographic distribution of performance using an interactive map  
- 🎯 Comparison between **Promoted vs Non-Promoted** sales (volume vs margin)  
- 🔽 Drill-down from **Country → Region → Pharmacy**

### 🔍 Key Insights
- Significant performance disparities exist within the same country, both in revenue generation and margin contribution.
- Pharmacies with similar revenue levels can achieve very different margins, highlighting operational efficiency differences.
- Urban pharmacies concentrate higher sales volume and revenue, while Suburban and Rural pharmacies can achieve comparable or higher margins.
- Promotions do not increase sales volume, requiring careful evaluation and control.
- High-performing regions and pharmacies provide strong internal benchmarks for network-wide optimization.

---
