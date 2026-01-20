# Pharmacy Sales & Profitability Analytics  
📊 Power BI Analytics Project

This project is developed in response to a **Pharmacy Sales & Profitability Analytics Data Challenge**, based on a European pharmacy distributor operating across multiple countries.

The objective is to build a Power BI report that enables stakeholders to understand **sales performance, profitability drivers, and geographic contributions** at multiple levels of detail.

> 🔧 **Project status**:  
> - Dashboard 1 (Business Performance Overview): ✅  
> - Dashboard 2 (Product Performance): 🚧 
> - Dashboard 3 (Pharmacy & Regional Insights): 🚧 

---

## 🎯 Challenge Objective

The goal of this project is to help stakeholders answer key business questions such as:

- How do **revenue, units sold, and margin** evolve over time?
- Which **countries and regions** contribute most to total revenue and margin?
- How does performance change when drilling down from **country → region → pharmacy**?
- How does **sales volume (units)** compare to **profitability (margin)** across markets?
- How do different **pharmacy types** and **products** impact overall performance?

The dashboards are designed to support **executive decision-making**, combining high-level KPIs with interactive drill-down analysis.

---

## 🗂️ Dataset Overview

The data model follows a **star schema**, optimized for analytical performance and scalability.

### Fact Table
- **FactSales** – daily sales transactions by pharmacy and product

### Dimension Tables
- **DimDate** – date, month, quarter, year
- **DimPharmacy** – country, region, city, pharmacy type
- **DimProduct** – product attributes

*# inserir imagem do modelo de dados*

---

## 📏 DAX Measures

Measures are grouped by analytical domain for clarity and maintainability.

### Revenue
- Revenue (€)
- Revenue MoM
- Revenue MoM %

### Units
- Units Sold
- Units Sold MoM
- Units Sold MoM %

### Margin
- Margin (€)
- Margin MoM
- Margin MoM %

---

## 🧭 Dashboard Structure

### 📝 Page 1: Business Performance Overview

This dashboard provides an **executive-level overview** of overall business performance.

#### KPIs
- **Revenue (€)** – total revenue with monthly sparkline
- **Units Sold** – total units sold with monthly sparkline
- **Margin (€)** – total margin with monthly sparkline

Sparklines are used to convey trend direction without duplicating detailed time-series visuals.

#### Key Insights

**Countries with the Highest Units Sold**
- Identifies markets with the largest sales volume
- Highlights demand distribution independently of pricing or margin

**Countries and Regions Contributing Most to Revenue and Margin**
- Compares absolute revenue versus profitability
- Enables drill-down from country to region
- Supports identification of high-revenue but low-margin markets

#### Interactive Filters
- Year
- Pharmacy Type
- Product Name

This page answers the briefing questions related to:
- Overall performance trends
- Country-level contribution
- Volume vs. profitability comparison

---

### 📝 Page 2: Product Performance (Planned)

This dashboard will focus on:
- Performance by **product category and brand**
- Comparison between **high-volume vs. high-margin products**
- Identification of products that may require pricing or promotion review

---

### 📝 Page 3: Pharmacy & Regional Insights (Planned)

This dashboard will focus on:
- Performance at **pharmacy level**
- Comparison between pharmacies within the same region
- Differences across **Urban, Suburban, and Rural** pharmacy types
- Geographic patterns in sales and profitability

---

## 🧠 Design Principles

- Clear separation between **overview and deep-dive analysis**
- Avoidance of redundant visuals
- Drill-down used instead of overcrowded charts
- Focus on business questions defined in the original briefing

---

## 🚀 Tools & Technologies

- Power BI Desktop
- DAX
- Star schema data modeling
- Interactive and drill-down visuals

---

## 📌 Notes

This project is part of a **Power BI analytics portfolio**, demonstrating the ability to translate a business briefing into a structured, scalable, and decision-oriented dashboard solution.
