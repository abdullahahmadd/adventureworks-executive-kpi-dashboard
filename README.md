# AdventureWorks Executive KPI Dashboard
### Microsoft Power BI Data Analyst Specialization - Portfolio Project

![Power BI](https://img.shields.io/badge/Power%20BI-yellow)
![Business Intelligence](https://img.shields.io/badge/Business%20Intelligence-green)
![Data Analytics](https://img.shields.io/badge/Data%20Analytics-blue)

---

## Table of Contents

- [Overview](#overview)
- [Business Task](#business-task)
- [Objectives](#objectives)
- [Dataset](#dataset)
- [Tools & Technologies](#tools--technologies)
- [Methodology](#methodology)
- [KPI Design & Forecasting](#kpi-design--forecasting)
- [Results](#results)
- [Key Performance Indicators](#key-performance-indicators)
- [Key Findings](#key-findings)
- [About This Project](#about-this-project)

---

## Overview

This project delivers an executive-level KPI dashboard built in Microsoft Power BI on the AdventureWorks dataset. It transforms raw sales and customer data into clear KPIs, trend lines, forecasts, and natural-language-accessible insights to support strategic decision-making at the executive level.

---

## Business Task

Enable AdventureWorks executives to:

- Monitor overall sales performance at a glance
- Track customer reach and geographic presence
- Identify top and underperforming product categories
- Analyze sales trends and forecast future performance
- Interact with data directly using natural language (Q&A)

---

## Objectives

- Build a single-page executive dashboard consolidating the most decision-relevant KPIs
- Model sales and customer data into a clean, relationship-based structure
- Apply monthly sales forecasting with seasonality to support forward planning
- Enable natural language querying so executives can explore data without needing report-building skills

---

## Dataset

| Table | Key Fields |
|---|---|
| Sales | Order Date, Order Total, Order Quantity, Product details, Order Status |
| Customers | Customer ID, City, Country, Membership Tier, Demographics |

The dataset combines transactional sales data with customer attributes, enabling both performance and demographic-level analysis in a single model.

---

## Tools & Technologies

| Category | Tools |
|---|---|
| Application | Microsoft Power BI Desktop |
| Forecasting | Power BI Analytics & Forecasting |
| Interaction | Q&A Natural Language Visual |

---

## Methodology

**1. Data Understanding**
Reviewed the Sales and Customers tables to identify the key business fields relevant to executive-level reporting.

**2. Data Preparation**
Verified data types and ensured clean, analysis-ready data before building any visuals in Power BI.

**3. Core Visualizations**
Built table, column chart, and line chart visuals to analyze products, categories, and sales trends.

**4. KPI Development**
Created KPI cards for Total Sales, Customer Reach, and Geographic Presence, giving executives an at-a-glance performance summary.

**5. Forecasting**
Applied monthly sales forecasting with seasonality and a high confidence interval to support forward-looking planning.

**6. Natural Language Analytics**
Enabled the Q&A visual so executives can ask business questions directly, without needing to navigate filters or build custom visuals.

**7. Executive Layout & Design**
Organized all visuals into a single, clean, executive-friendly dashboard layout prioritizing scannability over density.

---

## KPI Design & Forecasting

- **KPI cards:** Total Sales, Customer Reach, Geographic Presence - built for at-a-glance executive review.
- **Forecasting approach:** Monthly sales forecast incorporating seasonality, generated with a high confidence interval to support planning decisions.
- **Q&A visual:** Enables ad hoc natural-language queries on top of the same data model, extending the dashboard beyond fixed visuals.

---

## Results

All screenshots in [`Results/`](./Results).

| # | Dashboard | Screenshot |
|---|-----------|------------|
| 1 | Executive Sales Overview - one-page dashboard with KPIs, sales trends, forecasting, and interactive insights | ![Executive Sales Overview](Results/AdventureWorks_Executive_Summary_Dashboard.png) |

---

## Key Performance Indicators

| KPI | Result |
|---|---|
| Lowest Average Order Value | Long Beach |
| Highest Average Order Quantity | BMX Bikes |
| Highest Product Weight (by subcategory) | Downhill |
| Forecast Basis | Monthly, with seasonality and high confidence interval |

---

## Key Findings

- **Long Beach** recorded the lowest average order value among all locations analyzed, signaling a potential pricing or demand issue worth further investigation.
- **BMX Bikes** showed the highest average order quantity of any product category, marking it as a high-volume driver worth prioritizing in inventory planning.
- The **Downhill** product subcategory carried the highest product weight, which has direct downstream impact on logistics and shipping costs.
- Sales trends show clear seasonality across the dataset, which supports the reliability of the monthly forecasting model built into the dashboard.

---

## About This Project

This project was developed as the final portfolio project for the Microsoft Power BI Data Analyst Professional Certificate. It reflects real-world executive reporting standards and demonstrates how Power BI can convert raw data into actionable business insight at the leadership level.

---
