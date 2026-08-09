# 🌪️ US Disaster Declarations Dashboard

An interactive **Microsoft Power BI Dashboard** that analyzes FEMA Disaster Declaration data across the United States. This project leverages **Power Query**, **DAX**, and a **Star Schema** data model to provide meaningful insights into disaster trends, geographic distribution, FEMA assistance programs, and scenario-based forecasting using a **What-If Parameter**.

---

## 📌 Project Overview

The objective of this project is to transform raw FEMA disaster declaration data into an interactive business intelligence dashboard that enables users to:

- Analyze disaster declarations across the United States.
- Identify disaster-prone states and designated areas.
- Track disaster trends over time.
- Compare FEMA assistance programs (IA, PA, HM, IH).
- Perform scenario analysis using a What-If Parameter.
- Support data-driven decision-making through interactive visualizations.

---

## 🚀 Features

- 📊 Executive Dashboard with KPIs
- 🗺️ Geographic Analysis using Maps
- 📈 Temporal Trend Analysis
- 📋 Incident & FEMA Program Insights
- 🎚️ What-If Scenario Analysis
- 🔍 Interactive Slicers & Filters
- ⚡ Optimized Star Schema Data Model

---

## 📊 Dashboard Pages

### 1️⃣ Executive Overview

Provides a high-level summary of disaster declarations through KPI cards and trend visualizations.

**Key Metrics**
- Total Disaster Declarations
- Total IA Declarations
- Total PA Declarations
- Total HM Declarations
- Average Disaster Duration

---

### 2️⃣ Geographic Analysis

Analyzes the geographical distribution of disasters across U.S. states.

**Visuals**
- Filled Map
- Top States by Disaster Count
- Top Designated Areas
- State Summary Tables

---

### 3️⃣ Temporal Trends

Analyzes disaster declaration patterns over time.

**Visuals**
- Monthly Disaster Trends
- Yearly Disaster Trends
- Average Disaster Duration Over Time
- Monthly Summary Table

---

### 4️⃣ Incident & Program Insights

Compares disaster incidents and FEMA assistance programs.

**Visuals**
- Program Declarations by Incident Type
- Scatter Chart
- Average Disaster Duration by Incident Type
- Incident Summary Table

---

### 5️⃣ Scenario Analysis

Uses a What-If Parameter to simulate changes in disaster declaration frequency.

**Features**
- Frequency Adjustment Slider
- Projected PA Funding
- Projected IA Declarations
- Scenario Analysis Line Chart

---

## 🛠️ Technology Stack

| Tool | Purpose |
|------|----------|
| Microsoft Power BI Desktop | Dashboard Development |
| Power Query (M) | Data Cleaning & Transformation |
| DAX | Business Calculations |
| CSV | Data Source |
| Star Schema | Data Modeling |

---

## 🧹 Data Preparation

Power Query was used to clean and transform the dataset.

### Transformations Performed

- Imported FEMA CSV dataset
- Promoted Headers
- Removed unnecessary columns
- Trimmed text values
- Cleaned non-printable characters
- Replaced invalid values (`NA`) with `Null`
- Converted columns to appropriate data types
- Created calculated columns
- Loaded cleaned data into the Power BI model

---

## 📐 Data Model

The project follows a **Star Schema** consisting of:

### Fact Table

- Fact_Disaster

### Dimension Tables

- Dim_Date
- Dim_State
- Dim_IncidentType
- Dim_DeclarationType

This model improves report performance, simplifies relationships, and enables efficient DAX calculations.

---

## 📊 DAX Measures

Major DAX measures include:

- Total Disaster Declarations
- Total IA Declarations
- Total PA Declarations
- Total HM Declarations
- Average Disaster Duration
- Average Time to Declaration
- Projected PA Funding
- Projected IA Declarations
- Frequency Adjustment Value


---

## 📈 Business Value

This dashboard helps users:

- Monitor disaster declaration trends.
- Identify disaster-prone regions.
- Analyze FEMA assistance programs.
- Understand historical disaster patterns.
- Forecast projected funding using What-If analysis.
- Support data-driven disaster management decisions.
---

## 📄 Documentation

This repository includes:

- 📘 User Guide
- 📙 Technical Documentation
- 📑 Project Presentation

---

## 👨‍💻 Author

**Yash N**

Microsoft Power BI Developer

---

## ⭐ If you found this project useful, please consider giving it a Star!
