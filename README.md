# 🚗 BMW Global Car Sales Dashboard (Power BI Project)

 [**View Live/Interactive Dashboard**](https://app.powerbi.com/view?r=eyJrIjoiYjZlMTZlYzYtNzk4MS00NmU1LWIxMzMtNzU4NTkwMzk3NDA3IiwidCI6IjljNmZkNWQ5LWMyMjgtNGIyMi1iZTljLTg5ZTk2NTgwZWRiMSJ9)

## 🧩 Problem Statement

Understanding sales performance across global regions, customer channels, and vehicle models is crucial for informed decision-making in the automotive industry. This dashboard provides BMW with powerful insights into sales patterns, regional performance, customer buying behavior, and revenue contributions from various product lines.

By identifying top-performing models, sales channels, and underperforming markets, the company can optimize marketing strategies, forecast demand, and enhance overall profitability. Interactive features also allow for deep-dive exploration of key metrics across time, model types, and geographies.

---

## 📊 Project Summary

This Power BI project visualizes BMW's global sales data in a clean, interactive, and visually compelling dashboard. It includes multi-layered analysis with dynamic filters and visuals, optimized through a robust data model and intuitive user experience.

### 🗃️ Dataset Overview

The dataset consists of sales transactions of BMW cars across different regions. Each row represents a sales record and contains the following fields:

| Column Name      | Description                                                                 |
|------------------|-----------------------------------------------------------------------------|
| `Date`           | Date of the transaction                                                     |
| `Year`           | Year of the sale                                                            |
| `Model`          | BMW car model sold                                                          |
| `Revenue`        | Revenue generated from the sale (in USD)                                    |
| `Quantity Sold`  | Number of units sold                                                        |
| `Region`         | Continent where the sale occurred                                           |
| `Country`        | Specific country of transaction                                             |
| `Channel`        | Sales channel used (e.g., Dealership, Online, Wholesale)                    |

---

## 🛠️ Key Project Steps

### 1. **Data Cleaning & Transformation (Power Query)**
- Handled null values and ensured consistency in data.
- Renamed and structured columns for clarity.
- Converted data types for optimal performance.
- Split data into **Fact** and **Dimension** tables.
- Performed **data modeling** by creating relationships between tables.

### 2. **Date Table Creation**
- A custom **Date Dimension** was created with fields like:
  - `Year`, `Month`, `Weekday` (e.g., Mon, Tue)
  - `WeekType` (Weekday or Weekend)
- Linked to the main fact table for advanced time-based filtering and slicing.

### 3. **DAX Measures**
Created several DAX measures to enable deeper business insights:
- **Total Revenue**
- **Total Cars Sold**
- **Top Selling Cars**
- **Revenue by Channel**
- **Sales by Region/Country**
- **Revenue Trend over Time**

### 4. **Visualizations**
- Clean, modern dashboard layout built using:
  - Cards, Pie Charts, Column Charts, Tables
  - Dynamic images for each car model
  - Filters/Slicers for **Region**, **Year**, **Channel**, **Country**, and **Model**

- A **second page** was created for **model-level insights**:
  - Clickable buttons per model
  - Dynamic visuals and image updates
  - Focused KPIs for individual car models

### 5. **Design & Aesthetic**
- A **custom PowerPoint background** was designed for the dashboard.
- Incorporated clean shapes, soft colors, and intuitive layout.
- Imported into Power BI for a polished, branded appearance.

---

## 💡 Business Insights Uncovered

- Identify **top-selling models** and their associated revenues.
- Reveal **regional and country-level trends** in customer demand.
- Understand **channel effectiveness** (e.g., Online vs Dealership).
- Assess **time-based patterns** in sales using date intelligence.
- Enable dynamic, self-service exploration via slicers and filters.

---

## 🔗 Access Dashboard & Dataset

* [**Dataset(CSV)**]()
* [**Power BI Dashboard (.pbix)**]()
* [**Live/Interactive Dashboard**](https://app.powerbi.com/view?r=eyJrIjoiYjZlMTZlYzYtNzk4MS00NmU1LWIxMzMtNzU4NTkwMzk3NDA3IiwidCI6IjljNmZkNWQ5LWMyMjgtNGIyMi1iZTljLTg5ZTk2NTgwZWRiMSJ9)
* [**Power BI Dashboard image 1 (Dashboard.png)**]()
* [**Power BI Dashboard image 2 (All Models.png)**]()

---

## 👨‍💻 Tools & Skills Used

- **Power BI (DAX, Power Query, Data Modeling)**
- **Data Cleaning & Transformation**
- **Interactive Data Visualization**
- **Design (PowerPoint Custom Backgrounds)**
- **Business Intelligence & Analytics**

---

## 📣 Contact

If you're interested in collaborating, feel free to reach out via [LinkedIn]().

---

> *This project showcases my passion for data storytelling, dashboard design, and business insight generation in real-world scenarios. Thank you for checking it out!*
