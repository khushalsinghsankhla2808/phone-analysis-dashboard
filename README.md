<div align="center">

# 📱 Phone Performance Analytics Dashboard

### 🚀 End-to-End Power BI Business Intelligence Project

<img src="https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black"/>
<img src="https://img.shields.io/badge/Data%20Analytics-Project-blue?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Dataset-958%20Smartphones-orange?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Brands-26-purple?style=for-the-badge"/>

<br><br>

> An advanced **Power BI dashboard** designed to analyze smartphone market trends, pricing behavior, processor performance, battery efficiency, RAM distribution, and 5G adoption across **958 smartphones and 26 brands**.

</div>

---

# 🌟 Project Highlights

✅ Executive-Level Dashboard Design  
✅ Advanced DAX Measures & KPIs  
✅ Interactive Business Intelligence Reporting  
✅ Market Trend & Pricing Analysis  
✅ 5G Adoption & Performance Benchmarking  
✅ Modern UI/UX Dashboard Experience  
✅ Data Cleaning & Transformation using Power Query  

---

# 📸 Dashboard Preview

<p align="center">
  <img width="100%" src="https://github.com/user-attachments/assets/cac40c0b-61b1-40de-953f-cca27d8d2c56">
</p>

---

# 📑 Table of Contents

- [📖 Overview](#-overview)
- [🎯 Business Objective](#-business-objective)
- [📊 Key KPIs](#-key-kpis)
- [✨ Dashboard Features](#-dashboard-features)
- [🔍 Key Insights](#-key-insights)
- [🧮 DAX Measures](#-dax-measures)
- [🛠️ Tech Stack](#️-tech-stack)
- [🗂️ Dataset Information](#️-dataset-information)
- [📂 Project Structure](#-project-structure)
- [🚀 How to Use](#-how-to-use)
- [🔮 Future Improvements](#-future-improvements)
- [🌐 Connect With Me](#-connect-with-me)
- [📜 License](#-license)

---

# 📖 Overview

The **Phone Performance Analytics Dashboard** is a complete Business Intelligence solution built using **Microsoft Power BI** to transform raw smartphone specification data into actionable insights.

This project enables stakeholders to:

- Analyze smartphone market trends
- Compare leading smartphone brands
- Evaluate processor performance
- Monitor 5G adoption trends
- Understand pricing distribution
- Identify high-value smartphone segments
- Explore battery and RAM patterns

The dashboard combines **interactive visuals, KPI monitoring, advanced DAX calculations, and executive storytelling** to deliver a modern analytics experience.

---

# 🎯 Business Objective

The primary objective of this dashboard is to provide a centralized analytics platform for smartphone market intelligence by:

- Monitoring smartphone performance trends
- Comparing pricing segments
- Evaluating brand market presence
- Tracking 5G adoption growth
- Identifying performance-focused devices
- Supporting data-driven business decisions

---

# 📊 Executive KPIs

<div align="center">

| KPI | Value |
|---|---|
| 📱 Total Smartphones | **958** |
| 🏷️ Total Brands | **26** |
| 💰 Average Price | **₹30.82K** |
| ⚡ Avg Performance Score | **36** |
| 📶 5G Adoption | **88%** |
| 🔋 Average Battery Capacity | **5,228 mAh** |

</div>

---

# ✨ Dashboard Features

## 📌 Executive Overview

- Interactive KPI Cards
- Brand Distribution Analysis
- Pricing Tier Analysis
- Top Performing Smartphones
- 5G Adoption Monitoring
- Battery & RAM Insights
- Processor Benchmarking

---

## 📌 Advanced Functionalities

✔️ Dynamic Slicers & Filters  
✔️ Interactive Drill-through Analysis  
✔️ Cross-Filtering Visuals  
✔️ Responsive Dashboard Layout  
✔️ Dynamic Tooltips  
✔️ Advanced DAX Calculations  
✔️ Executive-Level Storytelling  

---

# 🔍 Key Insights

## 📌 Market Insights

➜ Samsung leads the smartphone market with the highest number of devices.  
➜ Android dominates with over 95% market share.  
➜ Budget and Mid-Range devices dominate the smartphone ecosystem.  
➜ Mid-Range smartphones provide the best balance of price and battery life.  

---

## 📌 Performance Insights

➜ Apple Bionic and Tensor processors deliver the highest performance scores.  
➜ Most smartphones fall within the medium-performance category.  
➜ Higher RAM configurations strongly correlate with premium pricing.  

---

## 📌 5G Adoption Insights

➜ Overall 5G adoption exceeds 77% across the dataset.  
➜ Apple achieves near-complete 5G implementation.  
➜ Some brands still maintain a high percentage of non-5G devices.  

---

# 🧮 DAX Measures

## 📌 Average Performance Score

```dax
Avg Performance Score =
AVERAGE('Smart_Phone'[Performance Score])
```

---

## 📌 5G Percentage

```dax
5G Percentage =
DIVIDE(
    COUNTROWS(
        FILTER(
            'Smart_Phone',
            'Smart_Phone'[Has 5G] = "Yes"
        )
    ),
    COUNTROWS('Smart_Phone')
) * 100
```

---

## 📌 Normalized Performance Score

```dax
Normalized Performance =
DIVIDE(
    AVERAGE('Smart_Phone'[Performance Score]),
    100
) * 100
```

---

## 📌 Value Score

```dax
Value Score =
DIVIDE(
    [Performance Score],
    AVERAGE('Smart_Phone'[Price])
) * 1000
```

---

# 🛠️ Tech Stack

<div align="center">

| Technology | Purpose |
|---|---|
| 📊 Microsoft Power BI | Dashboard Development |
| ⚙️ Power Query | Data Cleaning & Transformation |
| 🧮 DAX | KPI Calculations & Data Modeling |
| 📁 Excel / CSV | Source Dataset |
| 🌐 GitHub | Version Control & Portfolio Showcase |

</div>

---

# 🗂️ Dataset Information

| Detail | Information |
|---|---|
| 📦 Dataset Size | 958 Smartphones |
| 🏷️ Total Brands | 26 |
| 📄 File Formats | CSV / XLSX |
| 📊 Main Columns | Brand, Price, RAM, Battery, Processor, 5G, OS, Performance Score |

---

# 🚀 How to Run the Project

## 1️⃣ Clone Repository

```bash
git clone https://github.com/khushalsinghsankhla2808/phone-analysis-dashboard.git```

---

## 2️⃣ Open Power BI File

```bash
Smart_Phone.pbix
```

Open using **Microsoft Power BI Desktop**

---

## 3️⃣ Refresh Dataset

```bash
Home → Refresh
```

---

## 4️⃣ Explore Dashboard

Use interactive slicers to analyze:

- Smartphone Brands
- 5G Adoption
- Processor Performance
- RAM Variants
- Pricing Segments
- Battery Trends

---

# 📂 Project Structure

```bash
📦 Phone-Performance-Analytics-Dashboard
 ┣ 📊 Smart_Phone.pbix
 ┣ 📄 Smart_Phone.csv
 ┣ 🖼️ dashboard_preview.png
 ┗ 📘 README.md
```

---

# 🔮 Future Improvements

- 📡 Real-Time API Integration
- 📱 Mobile Responsive Layouts
- 🤖 AI-Based Recommendation System
- 📈 Forecasting & Predictive Analytics
- 💬 Customer Sentiment Analysis

---

# 🌐 Connect With Me

<div align="center">

## 👨‍💻 Khushal Singh Sankhla

<p align="center">
  <a href="https://github.com/khushalsinghsankhla280804">
    <img src="https://img.shields.io/badge/GitHub-khushal280804-black?style=for-the-badge&logo=github">
  </a>

  <a href="https://www.linkedin.com/in/khushal-singh-sankhla/">
    <img src="https://img.shields.io/badge/LinkedIn-Khushal%20Singh%20Sankhla-blue?style=for-the-badge&logo=linkedin">
  </a>

  <a href="mailto:khushalsinghsankhla203@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact-red?style=for-the-badge&logo=gmail">
  </a>
</p>

</div>

---

# 📜 License

This project is licensed under the **MIT License**.

You are free to use, modify, and distribute this project for personal or commercial purposes.

---

# ⭐ Show Your Support

If you found this project valuable:

⭐ Star the Repository  
🍴 Fork the Project  
📢 Share Feedback  
🤝 Connect on LinkedIn  

---

<div align="center">

# 🚀 Transforming Raw Data into Actionable Insights

### ❤️ Built with Microsoft Power BI & Data Analytics

</div>
