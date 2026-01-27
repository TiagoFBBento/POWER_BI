# Pharmacy Sales & Profitability Analytics  
📊 Power BI Portfolio Project

This project is part of my **data analytics portfolio** and was developed using **Power BI** in response to a *Pharmacy Sales & Profitability Analytics Data Challenge*.

The dataset represents a **European pharmacy distributor operating across multiple countries**, with daily sales transactions by pharmacy and product.  
The goal of the project is to demonstrate how data can be transformed into **clear, actionable insights** that support business decision-making — even for users without a technical or analytics background.

---

## 🧩 Stakeholder Questions (From the Original Briefing)

The dashboards were designed to answer a specific set of **business questions defined in the original challenge briefing**.  
These questions reflect the type of information stakeholders typically need to make informed decisions.

The report addresses the following questions:

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

Each dashboard in the report answers a specific subset of these questions, following a clear analytical narrative.

---

## 🧠 Project Objective (Plain Language)

The main objective of this project is to help business stakeholders understand:

- **How the business is performing overall**
- **Where sales and profitability come from**
- **Which markets, products, and pharmacies drive results**
- **Where performance differs despite similar contexts**
- **How commercial decisions (such as promotions) impact results**

To achieve this, the report is structured into **three dashboards**, progressing from a high-level overview to detailed, local-level analysis.

---

## 🗂️ Data Overview

The dataset contains **daily sales transactions** across multiple pharmacies and products.  
Each transaction includes information about:

- Date of sale
- Pharmacy and geographic location
- Pharmacy type (Urban, Suburban, Rural)
- Product, category, and brand
- Revenue, units sold, and margin

The data model follows a **star schema**, which is a standard and efficient structure for analytical reporting.

---

## 📐 Key Metrics Explained

The report focuses on three core business metrics that are easy to interpret:

- **Revenue (€)**  
  Represents sales scale and market size.

- **Units Sold**  
  Represents demand and sales volume.

- **Margin (€ and %)**  
  Represents profitability:
  - Margin (€) shows total profit contribution.
  - Margin (%) shows efficiency, allowing fair comparisons between markets of different sizes.

> Instead of using a generic “profit” metric, margin is used to clearly separate **scale** from **efficiency**, which is critical for meaningful comparisons across countries, regions, and pharmacies.

---

## 🧭 Dashboard Structure & Purpose

### 🟦 Dashboard 1 — Business Performance Overview

**Purpose:**  
Provide an executive-level snapshot of overall business performance.

**What it shows:**
- Total revenue, units sold, and margin
- Performance trends over time
- Comparison between countries and regions
- Identification of high-volume vs high-profitability markets
- Year comparison (2024 vs 2025)

**Stakeholder questions answered:**
- Overall performance trends
- Country and region contribution
- Volume vs profitability at a macro level

---

### 🟨 Dashboard 2 — Product & Category Performance

**Purpose:**  
Understand how products, brands, and categories perform.

**What it shows:**
- Revenue and margin by product category
- Most profitable categories and brands
- A scatter plot comparing:
  - Units sold (volume)
  - Margin % (profitability)
- Drill-down from **category → brand → product**

This visual approach highlights:
- Products that sell a lot but generate low margin
- Products that sell less but are highly profitable

**Stakeholder questions answered:**
- Best-performing categories and brands
- High-volume vs high-margin trade-offs
- Pricing and portfolio optimization opportunities

---

### 🟩 Dashboard 3 — Pharmacy & Regional Insights

**Purpose:**  
Analyze performance at a local and operational level.

**What it shows:**
- Sales and profitability by country, region, and pharmacy
- Performance differences within the same country
- Comparison between Urban, Suburban, and Rural pharmacies
- Geographic patterns using an interactive map
- Comparison between promoted and non-promoted sales

**Stakeholder questions answered:**
- Regional contribution to overall results
- Identification of outperforming and underperforming pharmacies
- Impact of pharmacy type on performance
- Impact of promotions on volume and profitability
- Geographic performance patterns

---

## 🧩 Interactivity & Usability

The report is designed to be **interactive and intuitive**, allowing users to:

- Filter by year, country, pharmacy type, and product
- Drill down from high-level views to detailed insights
- Explore data without requiring technical knowledge

This ensures the report supports **exploration, storytelling, and decision-making**.

---

## 🛠️ Tools & Technologies

- **Power BI Desktop**
- **DAX (Data Analysis Expressions)**
- Star schema data modeling
- Interactive visuals with drill-down
- ZoomCharts Drill Down visuals

---

## 🎯 Why This Project Matters

This project demonstrates the ability to:

- Translate a business briefing into a structured analytics solution
- Design dashboards that are both **informative and accessible**
- Balance technical accuracy with business clarity
- Communicate insights effectively to non-technical audiences

It showcases **end-to-end analytical thinking**, from data modeling to insight delivery, and is intended as part of a professional analytics portfolio.
