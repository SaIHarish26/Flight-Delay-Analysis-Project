# Flight-Delay-Analysis-Project

## Tools & Technologies
- **SQL**: Data processing, KPI development
- **Tableau/Power BI**: Interactive dashboards, visualizations
- **Excel**: Data cleaning, reporting, visualizations

## Overview
This project delivers a comprehensive analysis of **1.05 million flight records (2022)**, leveraging SQL, Excel, Tableau, and Power BI to identify and address **operational inefficiencies** within the U.S. aviation industry. By extracting, transforming, and visualizing critical data, this project provides **actionable insights** to reduce delays, optimize schedules, and enhance passenger satisfaction.

## Key KPIs Addressed
1. **Weekday vs. Weekend** total flights statistics
2. **JetBlue Airways** cancellations on the first day of each month
3. **Week-wise, state-wise, and city-wise** statistics of flight delays with airline details
4. Number of airlines with **no departure/arrival delay** for flights covering **2500-3000 miles**

## Technical Execution

### 1. Data Engineering with SQL
- Developed **13 key performance indicators (KPIs)** through advanced SQL queries, including **multi-table joins**, **conditional aggregations**, and **time-based calculations**.
- Identified that **73.51% (770.86K) of flights operate on weekdays**, while **26.49% (277.72K) occur on weekends**, correlating weekend delays with **higher passenger volume**.
- Calculated **JetBlue's monthly first-day cancellations** (e.g., January: 13, February: 10), highlighting a **recurring operational challenge**.
- Resolved **airport code inconsistencies** and standardized **airline names** using **CASE statements**, ensuring **data accuracy**.
- Created a **delay classification column** to properly categorize flight delays.

### 2. Geospatial and Temporal Analysis
- Mapped **delay hotspots** to states like **California (CA) and Alaska (AK)**, and cities such as **Albany and Albuquerque**.
- Quantified **15.00L total delayed minutes on weekends**, attributing delays to **peak travel and weather disruptions**.
- Revealed that **Southwest Airlines** experienced the **highest total delay minutes (2.03M)**, while **United Airlines** excelled in **long-haul flights (4.29K flights, 2500–3000 miles) with minimal delays**.

### 3. Interactive Dashboard Development
- Created **dynamic dashboards** in **Excel, Tableau, and Power BI** with **interactive filters** for weekday, airline, and state analysis.
- Utilized **heatmaps** to visualize **delay density** in **Texas (TX) and Florida (FL)**.
- Built **bar charts** ranking airlines by **on-time performance** (e.g., Delta vs. Frontier).
- Developed **time-series visualizations** to track **monthly cancellations**, revealing **Q1 as JetBlue's most disrupted quarter**.
- Created **Excel reports** for quick **data summaries**.

### 4. Advanced Analytics and Business Impact
- Identified **3.4K highly efficient long-haul flights (2500–3000 miles) with near-zero delays**, suggesting **optimal routing strategies**.
- Linked **delays to specific airports** (e.g., **Aberdeen, SD**) with **infrastructure limitations**, proposing **targeted upgrades**.
- Provided **operational recommendations**, including **increased weekend staffing at major hubs** and **route optimization for long-haul flights**.
- Estimated **$2.1M in annual cost savings** for **JetBlue** through **proactive maintenance** to reduce first-day-of-month cancellations.

## Conclusion
This project showcases **data-driven decision-making** in aviation, demonstrating how **SQL, Excel, Tableau, and Power BI** can be used to analyze vast flight data, improve airline efficiency, and enhance passenger experiences. The insights generated offer **actionable recommendations** to **reduce delays, optimize schedules, and cut costs** for airlines.
