# 📊 Airbnb Comparative Analysis Dashboard (Chicago vs. New Orleans)

An interactive, data-driven Power BI dashboard analyzing Airbnb market metrics, room availability, pricing tiers, and host dynamics across Chicago and New Orleans.

---

## 📌 Project Overview
This project transforms raw short-term rental data into actionable business intelligence. Built using Power BI, the dashboard offers an end-to-end comparative analysis between two distinct travel markets, highlighting pricing strategies, geospatial listing densities, and host commercialization.

---

## 🔑 Key Insights & Dashboard Features

- **Geospatial Mapping:** Interactive map detailing exact listing locations, custom hover tooltips (Price, Neighborhood, Name), and city-level cross-filtering.
- **KPI Summary Cards:** Core performance metrics including Total Listing Volume, Average Daily Price, Unique Host Count, and Average 365-Day Availability.
- **Market Composition:** Donut chart breakdown showing market share across Room Types (*Entire home/apt*, *Private room*, *Shared room*, *Hotel room*).
- **Popularity & Pricing Breakdown:** 
  - Top 10 Neighborhoods filtered dynamically by listing count.
  - Price Tier Distribution (*Budget*, *Mid-Range*, *Luxury*).
- **Host & Activity Analysis:**
  - Single vs. Commercial Host market distribution.
  - Scatter plot examining Price vs. Review volume across room categories.

---

## 🛠️ Tech Stack & Tools Used
- **Business Intelligence Tool:** Microsoft Power BI Desktop
- **Data Source:** Airbnb Listing Dataset (Chicago & New Orleans)
- **Design & Layout:** Custom 1280x1100 px canvas, Airbnb brand aesthetic (`#FF5A5F` coral palette with semi-transparent card containers)

---

## 📂 Repository Structure

```text
├── Airbnb_Comparative_Dashboard.pbix   # Primary Power BI Project File
├── data/                               # Cleaned CSV Datasets
│   ├── chicago_listings.csv
│   └── new_orleans_listings.csv
├── assets/                             # Screenshots and visual elements
└── README.md                           # Project Documentation
