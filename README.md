# 📊 Multi-Year Sales Performance Dashboard

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:00F7FF,50:0078D4,100:0f2027&height=220&section=header&text=Sales%20Performance%20Analytics&fontSize=45&fontColor=ffffff&animation=fadeIn" alt="Header"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white" alt="Excel"/>
  <img src="https://img.shields.io/badge/Power%20Query-0078D4?style=for-the-badge&logo=microsoftexcel&logoColor=white" alt="Power Query"/>
  <img src="https://img.shields.io/badge/Business%20Intelligence-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="BI"/>
  <img src="https://img.shields.io/badge/Data%20Modeling-003B57?style=for-the-badge&logo=postgresql&logoColor=white" alt="Modeling"/>
</p>

---

## 📈 Executive Metrics
<p align="center">
  <img src="https://img.shields.io/badge/Total_Sales-$977K-blue?style=for-the-badge" alt="Sales"/>
  <img src="https://img.shields.io/badge/Total_Profit-$18K-green?style=for-the-badge" alt="Profit"/>
  <img src="https://img.shields.io/badge/Years-2016--2019-orange?style=for-the-badge" alt="Years"/>
</p>

---

## 📌 Project Overview
This project presents a **multi-year sales performance analysis dashboard** built entirely using **Microsoft Excel** with advanced BI techniques. The solution transforms raw sales data into a structured analytical model and delivers a fully interactive executive dashboard.

### 📐 Analytical Workflow
```mermaid
graph TD
    A[Raw Sales Data] --> B[Power Query ETL]
    B --> C[Power Pivot Data Model]
    C --> D[DAX Measure Creation]
    D --> E[Interactive Dashboard Design]
    E --> F[Executive Insights]
```

---

## 🛠️ Technical Implementation

<details>
<summary><b>1. Data Preparation (ETL)</b></summary>
<br>
<ul>
  <li><b>Tool:</b> Power Query.</li>
  <li>Standardized transactional records across multiple spreadsheets.</li>
  <li>Cleaned geographic discrepancies (State/City normalization).</li>
  <li>Handled outliers and missing profit values.</li>
</ul>
</details>

<details>
<summary><b>2. Star Schema Data Modeling</b></summary>
<br>
<ul>
  <li><b>Tool:</b> Power Pivot.</li>
  <li>Built relationships between Fact and Dimension tables.</li>
  <li>Dimension Tables: `Calendar`, `Geography`, `Products`, `Customers`.</li>
  <li>Optimized for fast slicing and dicing across massive datasets.</li>
</ul>
</details>

---

## 📊 Business Insights
*   **🌍 Regional Dominance:** The **Western region** leads in total sales volume, but profit margins vary significantly by product category.
*   **📦 Logistics Impact:** **Standard Class shipping** accounts for 60% of the volume, suggesting a price-sensitive customer base.
*   **🏆 Customer Value:** The top 10 customers contribute disproportionately to the bottom line, indicating a strong Pareto effect.

---

## 👤 Author
**Mohamed Salah Abdelhamid**
*   LinkedIn: [mohamedsalah-abdelhamid](https://www.linkedin.com/in/mohamedsalah-abdelhamid/)
*   GitHub: [@mohamedsalahabdelhamid](https://github.com/mohamedsalahabdelhamid)

---
<div align="center">
  <sub>Built with ❤️ by Mohamed Salah</sub>
</div>
