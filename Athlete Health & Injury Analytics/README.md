# Athlete Health & Injury Analytics

This project is part of my **data analytics portfolio** and was developed using **Power BI** in response to an *Athlete Health & Injury Data Challenge*.

Report:  
> [Power BI Report – link here]

---

## 🧠 Project Objective

The objective of this project is to support sports organizations in gaining a clear and integrated understanding of athlete health and injury dynamics. The analysis enables stakeholders to assess injury occurrence patterns, understand the operational impact of athlete downtime, and evaluate recovery effectiveness across different contexts.  

In high-performance sports environments, injuries directly affect player availability, competitive outcomes, and operational costs. This report aims to move beyond isolated injury counts by providing a structured analytical view that highlights where injury risk is concentrated, which injuries generate the highest impact, and how recovery processes perform in practice.  

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

## 🗂️ Data Overview

The dataset includes information about:

- Injury occurrence date  
- Athlete characteristics (age, gender, position)  
- Sport, event, and competitive context  
- Injury type and severity  
- Treatment and recovery method  
- Recovery duration and days lost  
- Team, coach, or regional context (when available)

The data model follows a **star schema**, which is a standard and efficient structure for analytical reporting and time-based analysis.

---

## 🔑 Key Metrics Explained

The report focuses on a core set of injury and performance-related metrics designed to be intuitive, comparable, and decision-oriented:

- **Total Injuries**  
  Represents the overall volume of injury occurrences.

- **Injury Rate**  
  Represents relative injury risk, enabling fair comparisons across athletes, sports, and contexts.

- **Days Lost**  
  Represents the direct operational impact of injuries on athlete availability.

- **Average Recovery Time**  
  Represents recovery efficiency and effectiveness of treatment processes.

- **Severity Index**  
  Captures injury impact by distinguishing between frequent low-impact injuries and less frequent high-impact injuries.

- **MoM and YoY (%)**  
  Represent time intelligence metrics calculated using a dedicated date dimension, allowing trend analysis and comparison over time.

All metrics used in the report are implemented as **custom DAX measures**, ensuring consistency across dashboards and drill-down levels.

---

## 🧭 Report Structure

### 🟦 Dashboard 1 - Injury Landscape & Risk Exposure

<img width="800" height="800" alt="image" src="<!-- image link here -->" />

### 🎯 Purpose
Provide an executive-level overview of injury frequency and risk exposure.

### 📊 What it shows
- **Total injuries and injury rate**
- **Injury trends over time**
- **Distribution of injuries by type**
- **Comparison across sports, events, and positions**
- **Segmentation by age group and gender**

### 🔍 Key Insights
- Injury occurrence is not evenly distributed across athletes or contexts.
- Specific sports, positions, and injury types concentrate a disproportionate share of injury risk.
- Clear exposure patterns emerge across age groups and competitive environments.

---

### 🟨 Dashboard 2 - Severity, Downtime & Operational Impact

<img width="800" height="800" alt="image" src="<!-- image link here -->" />

### 🎯 Purpose
Assess the real operational impact of injuries on athlete availability and performance.

### 📊 What it shows
- **Total and average days lost**
- **Injury severity by type and context**
- **Frequency vs impact analysis**
- **Comparison across sports, positions, and demographic groups**

### 🔍 Key Insights
- A relatively small number of injury types accounts for the majority of athlete downtime.
- Less frequent injuries can generate disproportionately high operational impact.
- Impact-based analysis enables better prioritization of prevention efforts.

---

### 🟩 Dashboard 3 - Recovery Effectiveness & Prevention Insights

<img width="800" height="800" alt="image" src="<!-- image link here -->" />

### 🎯 Purpose
Evaluate recovery effectiveness and identify opportunities for injury prevention.

### 📊 What it shows
- **Average recovery time by injury type and treatment method**
- **Comparison across teams, coaches, or contexts**
- **Trends in recovery efficiency over time**
- **Identification of low-injury-rate and fast-recovery contexts**

### 🔍 Key Insights
- Recovery outcomes vary significantly depending on treatment approaches and context.
- Certain teams or environments consistently achieve faster recovery and lower injury rates.
- Data-driven prevention and recovery optimization directly improve athlete availability and performance.

---
