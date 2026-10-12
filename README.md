<div align="center">

# 🚕 Bolt Supply & Demand Performance Analysis

<img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI"/> <img src="https://img.shields.io/badge/DAX-2C5364?style=for-the-badge" alt="DAX"/> <img src="https://img.shields.io/badge/Deneb%20%2F%20Vega--Lite-34B233?style=for-the-badge" alt="Deneb %2F Vega--Lite"/> <img src="https://img.shields.io/badge/HTML%20Content-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML Content"/>

*A Bolt-branded, fully cross-filtered dashboard that matches rider demand with driver supply — hour by hour, day by day.*

</div>

---

## ❓ Business questions

- When do riders search for a car but no driver is available?
- Which hours have the highest utilization and the biggest missed-trip opportunity?
- When should drivers go online to maximize earnings?
- How does the price multiplier (surge) behave across the week?

## 🗂 Data

Ride-hailing operational data in three related tables — **Searches** (unique searches, searches with no car, coverage %, price multiplier), **Activities** (online hours, booking hours, total rides) and **Hours / Calendar** dimensions.

## 📊 What's inside

- **Demand vs supply throughout the week** — unique searches against online driver hours
- **Driver guide: when to go online** — hours where demand exceeds supply
- **Price multiplier schedule** — surge pattern by weekday and hour
- **Trips: actual vs possible** — completed rides vs estimated trips at maximum coverage
- **Top 5 utilized hours** — where the fleet is busiest
- Custom **Deneb (Vega-Lite)** visual, 1280×720, fully cross-filtered, styled in Bolt brand colors

## 🧠 Skills demonstrated

- Custom visual design with Deneb / Vega-Lite specifications
- Star-schema data model with Calendar and Hours dimensions
- DAX KPIs: coverage %, utilization, estimated trips at max coverage
- Translating operational data into actionable guidance for drivers

---

## 🚀 How to open

1. Install [Power BI Desktop](https://www.microsoft.com/power-platform/products/power-bi/desktop) (free).
2. Download **`bolt-supply-demand-analysis.pbix`** from this repository.
3. Open it in Power BI Desktop and interact with the slicers and visuals.

---

<p align="center">
Built by <a href="https://github.com/eli-isa"><b>Ali Isa Ashrafli</b></a> · Data Analyst · Baku, Azerbaijan<br/>
⭐ If you find this project useful, consider giving it a star!
</p>
