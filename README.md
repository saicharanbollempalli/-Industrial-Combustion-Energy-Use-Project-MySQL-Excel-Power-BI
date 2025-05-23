# Industrial Combustion Energy Use Project – Data-Driven Insights with MySQL, Excel & Power BI

![Tools](https://img.shields.io/badge/Tools-MySQL%2C%20Power%20BI%2C%20Excel-brightgreen)
![Status](https://img.shields.io/badge/Status-Completed-blue)
![Dataset Size](https://img.shields.io/badge/Data%20Size-20K%2B%20Records-orange)

---

## 📌 Table of Contents
- [Overview](#overview)
- [Key Features](#key-features)
- [Project Workflow](#project-workflow)
- [Power BI Dashboard](#power-bi-dashboard)
- [KPIs Summary](#kpis-summary)
- [Tech Stack](#tech-stack)
- [How to Run This Project](#how-to-run-this-project)
- [Conclusion](#conclusion)
- [Resources](#resources)

---

## 📊 Overview
This end-to-end analytics project explores industrial combustion energy consumption patterns across the U.S. Using a combination of MySQL, Excel, and Power BI, it uncovers trends and insights in energy usage (MMBtu and GWht), identifies inefficiencies, and supports data-driven decision-making for sustainability.

---

## 🚀 Key Features
- 🔎 **Energy Consumption Insights** – Region-wise and facility-level analysis
- 📊 **Fuel Type Breakdown** – MMBtu & GWht analysis by fuel
- 📍 **Regional Energy Distribution** – MECS region-wise shares
- 🧮 **KPI Cards** – Total consumption, company averages, peak contributors
- 🎛️ **Dynamic Filters** – Country-wise filtering using slicers

---

## 🔄 Project Workflow

1. **Excel (Data Cleaning & Preprocessing)**
   - Removed nulls, standardized units, ensured schema consistency

2. **MySQL (Data Modeling & KPIs)**
   - Structured tables, joined datasets, executed transformation logic
   - Created derived metrics (e.g., % share, company fuel usage)

3. **Power BI (Visualization)**
   - Created interactive dashboard with charts, tables & slicers
   - Enhanced UX using bookmarks and visual-level filters

---

## 📈 Power BI Dashboard

![Dashboard Screenshot](ICE%20DASHBOARD.png)

**Key Visuals:**
- 💡 *Fuel Type vs MMBtu* (bar chart)
- 📍 *MECS Region Share* (summary table)
- 🏢 *GWht per Company Unit* (horizontal bar chart)
- 📟 *Total KPIs* –  MMBtu, GWh, Company Avg
- 🗃️ *Dynamic slicers by country & region*

---

## 📌 KPIs Summary

| Metric                          | Value       |
|-------------------------------|-------------|
| 🔥 MMBtu Total                 | 940.94K     |
| ⚡ GWh Total                   | 275.76      |
| 🏢 Avg GWh/Facility (3M Co.)  | 137.88      |
| 📊 Peak Fuel Type (Ethane)    | 5.6M MMBtu  |
| 🌍 Top Region (South)         | 47.13%      |

📄 *For full KPI documentation, see:* `ICE PROJECT KPIs.pdf`

---

## ⚙️ Tech Stack
- **MySQL** – For querying, modeling & aggregating KPIs
- **Excel** – For raw data preprocessing
- **Power BI** – For dashboard design and user interactivity

---

## 🛠️ How to Run This Project

1. Clone the repo:
   ```bash
   git clone https://github.com/saicharanbollempalli/-Industrial-Combustion-Energy-Use-Project-MySQL-Excel-Power-BI.git

