# 🇮🇳 India Waste Management & Recycling Analytics

> A Power BI analytics project focused on understanding waste generation, processing capacity, recycling performance, sustainability, and operational efficiency across India.

---

## 📌 Project Overview

India's growing waste generation creates challenges related to collection, processing, recycling, treatment, and landfill dependency.

This project uses **Power BI, Power Query, and DAX** to analyze waste-management data across Indian states, regions, cities, waste categories, and treatment methods.

The dashboard is designed to answer two key business questions:

- Where is India's waste-management system losing efficiency?
- Which areas show higher potential for recycling, treatment, and operational improvement?

---

## 🎯 Business Objectives

The project aims to:

- Analyze overall waste generation trends.
- Compare waste generation with processing capacity.
- Identify processing gaps.
- Evaluate collection and recycling performance.
- Analyze waste segregation and treatment pathways.
- Compare sustainability performance across states.
- Understand operational efficiency across city categories and regions.
- Identify areas where waste-management processes can be improved.
- Present actionable insights through an interactive Power BI dashboard.

---

## 🛠️ Tools & Technologies

| Tool / Technology | Purpose |
|---|---|
| **Power BI** | Dashboard development and data visualization |
| **Power Query** | Data cleaning and transformation |
| **DAX** | Measures and KPI calculations |
| **CSV** | Primary dataset |
| **Power BI Maps** | Geographic analysis |
| **GitHub** | Project documentation and portfolio |

---

## 📊 Dataset Overview

The dataset contains approximately **25,000 records** covering:

- **36 States / Union Territories**
- **130 Cities**
- **2015–2026**
- **9 Waste Types**
- **6 Treatment Methods**
- Multiple regions and city categories

### Key Data Fields

The analysis uses variables such as:

- Daily Waste Generation
- Waste Processing Capacity
- Collection Efficiency
- Waste Segregation Rate
- Recycling Rate
- Landfill Dependency
- Waste Management Budget
- Cost Per Ton
- Waste Management Workers
- Collection Vehicles
- Collection Frequency
- Smart Bins
- Carbon Emissions
- AQI
- Population
- Population Density
- Sustainability Index
- Municipal Efficiency Score
- Waste Type
- Treatment Method
- State
- City
- Region
- City Category
- Year

---

# 📑 Dashboard Structure

The Power BI dashboard contains **4 analytical pages**.

## 1️⃣ National Overview

Provides a high-level view of India's waste-management system.

### Key KPIs

- Total Waste Generated
- Processing Capacity
- Processing Gap
- Collection Efficiency
- Recycling Rate
- Landfill Dependency

### Key Analysis

- Waste Generation Trend
- Waste Generation by Waste Type
- Waste Generation vs Processing Capacity by State
- Regional Waste Management Performance

---

## 2️⃣ Recycling & Treatment Potential

Focuses on recycling, segregation, and treatment performance.

### Key KPIs

- Average Recycling Rate
- Average Segregation Rate
- Average Composting Rate
- Landfill Dependency

### Key Analysis

- Recycling Rate by Waste Type
- Collection Efficiency vs Recycling Rate
- Treatment Pathway by Waste Type
- Recycling Performance Across States

This page helps identify differences between waste collection, recycling, segregation, and treatment pathways.

---

## 3️⃣ Sustainability & Operational Efficiency

Evaluates environmental sustainability and operational performance.

### Key KPIs

- Sustainability Index
- Municipal Efficiency
- Collection Efficiency
- Average Segregation Rate
- Carbon Emissions

### Key Analysis

- Sustainability Performance by State
- Collection Efficiency vs Recycling Rate
- Collection Efficiency by City Category
- Infrastructure & Municipal Efficiency

---

## 4️⃣ Key Insights & Recommendations

An executive-summary page designed to convert dashboard analysis into actionable business insights.

### Key Focus Areas

- Processing Capacity Gap
- Recycling Performance
- Waste Segregation
- Landfill Dependency
- State-level Sustainability
- Operational Efficiency

### Example Recommendations

- Strengthen source-level waste segregation.
- Improve recycling and material recovery pathways.
- Expand processing capacity in high-gap areas.
- Improve collection infrastructure across city categories.
- Reduce dependence on landfill-based treatment.
- Focus investment on areas with measurable operational gaps.

---

# 📈 Key Dashboard Metrics

| Metric | Dashboard Value |
|---|---:|
| Total Waste Generated | **5.64M TPD** |
| Processing Capacity | **5.41M TPD** |
| Processing Gap | **223.99K TPD** |
| Collection Efficiency | **62.2%** |
| Average Recycling Rate | **36.68%** |
| Average Segregation Rate | **55.87%** |
| Average Composting Rate | **14.80%** |
| Landfill Dependency | **45.5%** |

> Note: KPI values represent the overall dashboard view and can change when filters are applied on analytical pages.

---

# 🧮 Key DAX Measures

Examples of measures created for the dashboard:

```DAX
Total Waste =
SUM('Waste_Management_India_20K'[Daily Waste Generation (TPD)])
