# 1️⃣ Athlete Health & Injury Analytics

This project is part of my **data analytics portfolio** and was developed using Power BI in response to a *Athlete Health & Injury Analytics Data Challenge*.

Report:

> https://app.powerbi.com/groups/me/reports/21faae20-a3a3-4fcb-a962-6fc9f3314626/6485b878aee349dca1e2?experience=power-bi

---

## 🧠 Project Objective

The objective of this project is to support sports stakeholders in gaining a **structured and evidence-based understanding of athlete injury risk**, enabling them to assess injury frequency, severity and recovery impact across different sports contexts.

It also aims to highlight risk differences across similar environments and to analyze the impact of contextual and medical decisions, such as competition level, playing surface and treatment methods on recovery outcomes. To address these objectives, the report is designed with a progressive structure, consisting of three dashboards that guide users from a high-level injury landscape overview to a detailed analysis of risk drivers and recovery performance.


---

## 🧩 Stakeholder Questions

- Which types of injuries occur most frequently?
- Which sports or events have the highest rate of injury?
- Are injuries more common in specific athlete age groups or genders?
- How does injury severity vary across different types of sports or positions?
- How long does recovery typically take for various injury types?
- Which treatment methods are most effective for speeding up recovery?
- Do certain coaches or teams have consistently lower injury rates?
- Are there regional differences in injury frequency or severity?
- Does the playing surface or competition level affect injury occurrence?

---

## 📁 Data Overview

The dataset provides a structured view of athlete injuries in competitive sports, combining injury frequency, severity, athlete characteristics, and contextual factors.

It includes information related to:

- **Injury occurrence and severity**
- **Athlete demographics** (age group, gender)
- **Sport and competition context**
- **Recovery time and treatment methods**

The data is modeled using a **star schema**, enabling efficient filtering, drill-down analysis, and consistent metric calculations across all dashboards.


<div align="center">
  <img 
    src="https://github.com/user-attachments/assets/1e85b198-2c30-4426-bb2e-2d00653a7c63" 
    alt="Power BI Data Model - Star Schema"
    width="500"
  />
  
  <br/>
  <sub><em>Power BI Data Model – Star Schema</em></sub>
</div>

---

## 🔑 Key Metrics Explained

The report focuses on a concise set of injury and recovery metrics designed to be intuitive, comparable, and decision-oriented, supporting both preventive and operational decisions.

- **Injuries**  
Represents the total number of recorded injury events, serving as the primary measure of injury frequency.

- **Injury Rate (%)**  
Normalizes injury occurrence relative to exposure, enabling fair comparisons across sports, teams, regions, and competitive contexts.

- **Severe Injury (%)**  
Indicates the proportion of injuries classified as severe, providing insight into injury seriousness beyond simple frequency.

- **Average Days to Recovery**  
Measures the average time required for athletes to fully recover from injuries, acting as a proxy for health impact and resource utilization.

- **YoY (%)**  
Year-over-Year variation metrics are used to assess structural changes in injury patterns, recovery outcomes, and risk exposure over time.

All metrics used in the report are implemented as **custom DAX measures**, ensuring consistent definitions, comparability across dashboards, and reliable drill-down analysis across seasons, sports, and organizational levels.

---

## 🧭 Report Structure

### 🟦 Dashboard 1 — Injury Landscape & Overall Risk Exposure

<img width="800" height="800" alt="image" src="https://github.com/user-attachments/assets/3fbc4f6a-da9f-4821-b7af-1df1bc1361b2" />

### 🎯 Purpose
Provide an executive-level overview of injury patterns across seasons, establishing the baseline injury landscape by combining frequency, severity, recovery impact, and geographic exposure before drilling into specific risk drivers.

### 📊 What it shows
- Total number of injuries and overall injury rate  
- Proportion of severe injuries and average days to recovery  
- Season-over-season comparison of injury indicators  
- Distribution of injuries by injury type  
- Identification of the most frequent injury types relative to the overall average  
- Geographic variation in injury frequency and severity by region  
- Comparison between high-volume and high-severity injury profiles across regions  

### 🔍 Key Insights
- The overall injury burden is consistently high across seasons, with stable injury rates and recovery times indicating a persistent impact on athlete availability rather than isolated anomalies.
- Injury occurrence is highly concentrated: a limited set of injury types (e.g. joint and muscle-related injuries) accounts for a disproportionate share of total cases.
- Some injury types combine high frequency with elevated recovery time, making them critical targets for preventive and medical intervention.
- Seasonal comparisons show limited volatility, suggesting that injury patterns are structurally embedded rather than driven by short-term fluctuations.
- Clear regional disparities exist in both injury volume and severity, highlighting differences in underlying risk exposure.
- Regions with higher injury counts do not necessarily present higher severity profiles, reinforcing the need to evaluate injury frequency and severity jointly when assessing overall risk.

---

## 🟨 Dashboard 2 — Injury Drivers & Athlete Risk Profiles

<img width="800" height="800" alt="image" src="https://github.com/user-attachments/assets/50c119aa-ed48-4daa-94d9-801a9e355b10" />

### 🎯 Purpose
Identify and quantify the main drivers of injury risk by athlete profile and competitive context, enabling stakeholders to understand *who* is most at risk and *under which conditions* injuries are more likely to occur.

### 📊 What it shows
- Injury frequency by age group and gender  
- Comparison of injury patterns between male and female athletes across age segments  
- Distribution of injury severity by sport  
- Identification of sports with higher proportions of severe injuries  
- Injury rate by playing surface type  
- Comparison of injury occurrence between amateur and professional competition levels  

### 🔍 Key Insights
- Injury frequency varies across age groups, with adult age segments showing consistently higher injury incidence compared to younger athletes.
- Male and female athletes display similar overall injury patterns, though differences emerge within specific age groups, suggesting the influence of demographic and physiological factors.
- Injury severity is not uniform across sports: certain sports exhibit a higher share of severe injuries despite similar overall injury volumes.
- Playing surface type has a measurable impact on injury occurrence, with indoor courts and grass surfaces associated with higher injury rates.
- Professional competition consistently shows higher injury rates than amateur levels, indicating increased physical demands and exposure.
- These findings confirm that injury risk is multi-dimensional, driven by a combination of athlete characteristics, sport-specific demands, and competitive context.

---

## 🟩 Dashboard 3 — Recovery, Treatment & Team Performance

<img width="800" height="800" alt="image" src="https://github.com/user-attachments/assets/5290467b-3214-423f-adf8-9759f98b39ef" />

### 🎯 Purpose
Evaluate the impact of injuries beyond their occurrence by analyzing recovery time, treatment effectiveness, and organizational patterns at team and coach level, supporting evidence-based medical and performance decisions.

### 📊 What it shows
- Average recovery time by injury type  
- Comparison of recovery duration across injury severity levels  
- Treatment effectiveness on recovery time, segmented by severity and observed consistently across multiple seasons  
- Team-level comparison using a relative injury rate index  
- Coach-level comparison using the same relative benchmark  
- Identification of teams and coaches that consistently perform above or below the overall injury average  

### 🔍 Key Insights
- Recovery time varies significantly by injury type, with ligament, muscle strain, and fracture-related injuries generating the highest average downtime.
- Injury severity is the dominant driver of recovery duration, with severe injuries requiring substantially longer recovery periods across all seasons.
- Across four seasons, treatment choice consistently influences recovery time for severe injuries, while minor injuries show limited sensitivity to treatment method.
- Absolute injury rate differences between teams and coaches are highly compressed, making relative indexing essential to identify meaningful performance gaps.
- A small subset of teams and coaches consistently exhibits higher injury rate indexes, indicating structural or methodological differences rather than isolated seasonal effects.
- These patterns suggest that recovery outcomes and injury prevention effectiveness are influenced not only by medical factors, but also by sustained organizational practices.

---
