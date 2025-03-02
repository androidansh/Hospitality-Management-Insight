# Hospitality Management Insights Dashboard

Welcome to the **Hospitality Management Insights Dashboard** project! This repository features an interactive Power BI dashboard built to deliver actionable insights for hotel revenue management. The project integrates multiple data sources from the hospitality domain and demonstrates my expertise in data analysis, visualization, and business intelligence.

---

## Table of Contents

- [Overview](#overview)
- [Data Description](#data-description)
- [Methodology](#methodology)
- [Dashboard Highlights](#dashboard-highlights)
- [Key Insights](#key-insights)
- [Technologies Used](#technologies-used)
- [How to Explore](#how-to-explore)
- [Conclusion](#conclusion)

---

## Overview

This project focuses on analyzing key performance indicators within the hospitality domain using real-world data. The goal is to empower hotel managers and revenue teams with insights to optimize pricing, manage occupancy, and improve overall performance. The interactive Power BI dashboard covers a range of metrics—from revenue by category to trends in occupancy and average daily rates (ADR).

---

## Data Description

The project utilizes the following CSV files:

- **dim_dates**: Contains detailed date information to support time-based analysis.
- **dim_hotels**: Includes hotel-related information such as hotel IDs, names, and locations.
- **dim_rooms**: Provides details about different room types and capacities.
- **fact_aggregated_bookings**: Offers aggregated booking data for revenue, occupancy, and related performance metrics.
- **fact_bookings**: Contains transactional booking details for granular analysis.

All these datasets have been integrated in Power BI to calculate and visualize important hospitality metrics.

---

## Methodology

1. **Data Preparation & Integration**  
   - **Cleaning & Merging:** Data from different CSV files was cleansed (handling missing values and duplicates) and joined using common keys (e.g., hotel_id, date).
   - **Aggregation:** Booking and revenue data were aggregated at various dimensions (by date, hotel, room type) to calculate key performance indicators.

2. **Exploratory Data Analysis (EDA)**  
   - Conducted initial EDA to understand trends and spot anomalies in the booking data.
   - Identified key metrics such as revenue, RevPAR (Revenue per Available Room), ADR (Average Daily Rate), and occupancy percentages.

3. **Dashboard Development in Power BI**  
   - **Calculated Measures:** Custom DAX measures were created for metrics like % Revenue by Category, Realisation %, and ADR by booking platform.
   - **Interactive Visuals:** Multiple visuals (bar charts, line charts, and trend graphs) were designed to show weekly performance, day type analysis (weekday vs. weekend), and platform-based performance.
   - **Slicers & Filters:** Interactive filters (e.g., by City and Room Type) allow users to drill down into specific segments.

---

## Dashboard Highlights

### Revenue & Performance Metrics
- **% Revenue by Category:**  
  - Visualizes revenue split between Luxury and Business segments.
- **Realisation % and ADR by Platform:**  
  - Compares key performance indicators across different booking platforms.
- **Trend Analysis by Key Metrics:**  
  - Displays trends over time for RevPAR, ADR, Occupancy %, and more (tracked week-by-week).

### Property & Day Type Analysis
- **Property-Level Insights:**  
  - Shows performance metrics (Revenue, RevPAR, ADR, Occupancy %) for individual properties across cities.
- **Day Type Comparison:**  
  - Compares performance between weekdays and weekends (e.g., ADR, Occupancy, and Realisation %).
- **Weekly Revenue & RevPAR:**  
  - Analyzes weekly changes, providing actionable insights for dynamic pricing and inventory management.

### Interactive Filters
- **Filter by City & Room Type:**  
  - Allow users to focus on specific geographical regions or room types to understand local market dynamics.

---

## Key Insights

- **Optimized Revenue Management:**  
  - High performance in specific segments (e.g., Luxury vs. Business) helps drive targeted marketing and pricing strategies.
- **Platform Performance:**  
  - Insights into Realisation % and ADR by booking platform support decision-making for channel management.
- **Trend Analysis:**  
  - Week-on-week trend analysis in RevPAR, ADR, and Occupancy % guides tactical adjustments during peak and off-peak periods.
- **Day Type Analysis:**  
  - Differentiating performance between weekdays and weekends helps tailor promotional offers and inventory allocation.

---

## Technologies Used

- **Power BI:**  
  - For interactive data visualization, dashboard creation, and DAX-based measure development.
- **DAX:**  
  - Custom formulas for calculating complex KPIs such as RevPAR, ADR, and growth rates.
- **CSV Data Files:**  
  - Source data provided via CSV files (dim_dates, dim_hotels, dim_rooms, fact_aggregated_bookings, fact_bookings).

---

## How to Explore

![Hospitality Domain-1](https://github.com/user-attachments/assets/6f202a3d-c227-490d-a9c1-83a88730ebbf)
![Hospitality Domain-2](https://github.com/user-attachments/assets/e69deff6-541b-4833-9af6-3210ffed520a)
![Hospitality Domain-3](https://github.com/user-attachments/assets/3397c8d1-b84a-41c2-8c87-d06c9b9b256a)
![Hospitality Domain-4](https://github.com/user-attachments/assets/d6db78e1-9217-4dbe-8049-b0ce5644ef2b)
![Hospitality Domain-5](https://github.com/user-attachments/assets/eab76a0d-55d8-4475-bcd8-6cfe9c24910d)
![Hospitality Domain-7](https://github.com/user-attachments/assets/02c6b086-b7e8-4bcb-890c-69f002f9adab)

## Conclusion

This project demonstrates an end-to-end approach to hospitality data analysis and dashboarding. By integrating multiple data sources and employing advanced visualization techniques, the dashboard provides actionable insights that can help hotels optimize revenue management and enhance operational performance. It is a testament to my ability to analyze complex datasets and translate them into strategic business insights.
