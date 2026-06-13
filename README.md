# 📊 Methane Emissions Dashboard (Jan–May 2026)

## 📝 Project Overview
This Power BI dashboard analyzes global methane (CH₄) emissions from January to May 2026. It integrates KPIs, sector contribution, geographic distribution, and time‑series analysis to highlight emission sources and trends.  

The `.pbix` file is **not shared publicly** to protect intellectual property. Instead, screenshots of the dashboard, model view, and mobile layout are provided for portfolio review.

---

## 📸 Screenshots
- **Dashboard View** → Full layout with KPIs, sector visuals, trend chart, map, and tables.  
- **Model View** → Fact, Dim, KPI Measures and Date tables showing clean separation and relationships.  
- **Mobile Layout** → Optimized design for recruiter accessibility.  
- **Interactive state** → Showing how every graphs, maps and data are connected.

*(Screenshots included in `/screenshots` folder of this repo)*  

---

## ⚙️ Data Model
- **Fact Table**: Original labels preserved for traceability.  
- **Dim Tables**: Clean separation for sources and dates.  
- **KPI_Measures Table**: Camel‑case naming, no units in DAX names. Units displayed in labels.  
- **Snapshot Month**: Linked to the DateTable for correct chronological slicing (Jan–May 2026).
---

## 📌 Key KPIs
- **Total Plumes Detected** → 8K  
- **Total Estimated Annual Emissions** → 8M t  
- **Emissions per Plume** → 935.5 t/plume  
- **Half‑Year Persistency** → Frequent vs Persistent, with totals and conditional formatting  


---

## 📊 Visuals
Treemap: Sector contribution (% share of emissions).
Line Chart (Snapshot Month): Monthly emissions trend (Jan–May 2026) using Snapshot Month from the DateTable.
Map: Geographic distribution by latitude/longitude.
Table: Top 10 sources by country.
Bar Chart: Emissions by sector.
Matrix: Persistency breakdown with totals and conditional formatting.

---

## 🎯 Design Choices
- **Clean DAX**: Camel case, no units in measure names.  
- **Clarity in visuals**: Units displayed in labels, not formulas.  
- **Consistency**: Sector colors aligned across visuals.  
- **Balance**: KPI row kept lean (no MoM variance card to avoid overcrowding).  
- **Portfolio polish**: README documents modeling decisions and design rationale.  

---

## 🚀 How to Use
- Explore screenshots for dashboard layout, model view, mobile design, and interactive view. 
- `.pbix` file available upon request for interview purposes only.  

---

## 📌 Notes for Recruiters

This project demonstrates:

- Strong **data modeling** (fact/dimension separation, Date table design, snapshot month linkage).
- Effective **time intelligence** (monthly emissions tracking, variance analysis).
- Professional **visual design** (clear layout, KPI-driven structure, recruiter-friendly readability).
- End-to-end dashboard development for **desktop, mobile, and interactive viewing experiences**.

---

## 📄 License
This repository is shared for portfolio demonstration purposes only.

The .pbix file is private and available only upon request for interview purposes.

No commercial use or redistribution of the dashboard file is permitted.

