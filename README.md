# Uber-Trips-Analysis
Uber Data Analysis: Strategic Growth &amp; Operational Insights

## Executive Summary
This project analyzes a dataset of 952 Uber trips to identify revenue drivers, service quality benchmarks, and geographical performance. By developing a multi-page interactive dashboard in Power BI, I transformed raw trip data into actionable insights regarding passenger behavior and financial efficiency.
- DashBoard
![Fare](https://github.com/user-attachments/assets/1c703713-13de-4984-91cb-8c1ef2223cfe)
![Category](https://github.com/user-attachments/assets/f55a88d7-4fef-4ad7-83ac-d801eb4c6505)
![Rating](https://github.com/user-attachments/assets/88854d78-ff94-4a0e-b54b-b966531b9504)
![Passengers](https://github.com/user-attachments/assets/7877d660-3e2a-49c0-8549-96a2c14a5c4c)
![uber measures](https://github.com/user-attachments/assets/c2a032cd-a05e-42ea-8007-0235779a3e47)

## Technical Skills Demonstrated
- ETL: Before importing the data into Power BI, I used Python to clean and transform the raw Uber trip logs.[My Python Script] (http://localhost:8888/notebooks/UberTrips.ipynb)

- Data Modeling: Implementation of a "Measures Table" for organized DAX management.

- Geospatial Analysis: Integrating Microsoft Bing maps to visualize global trip distribution.


## Data Architecture & Measures (DAX)
To provide deep analytical layers, I created a dedicated table of "My Measures". These measures allow for dynamic filtering across years and trip purposes.

### Key Financial & Operational Measures
- Avg Fare By Miles: Calculated as Total Fare / Total Miles, currently standing at 1.60.

- CARG (Compound Annual Rate of Growth): A custom growth metric calculated at 0.81 to track performance over time.

- Trip Frequency: Automated measures for Trips Count and Total Miles (18K) to monitor fleet utilization.

- Time Intelligence: Created specific measures for Fare2020 through Fare2025 to enable year-over-year comparative analysis.

## Dashboard Deep Dive
### 1. Revenue & Fare Performance
- High-Value Days: Thursday and Sunday represent the peak days for trip volume and total fare.

- Purpose-Driven Revenue: Commuting and Meal/Entertainment are the primary revenue engines, representing 21% and 20% of total fare respectively.

- Efficiency: The Bottom 5 Avg Fare By Miles visual identifies specific "Start" locations where profitability is lowest, highlighting areas for potential pricing adjustments.

### 2. Operational Categories & Preferences
- Car Preference: The fleet is well-balanced between Economy (338 trips), SUV (311 trips), and Premium (303 trips).

- Trip Type: A significant majority (72%) of trips are Round-Trip, suggesting a loyal user base or specific use cases like business meetings.

- Payment Ecosystem: Users show no single dominant payment preference, with Uber Credit (35%) and Card (33%) being nearly equal.

### 3. Service Quality & Geography
- Rating Distribution: The Avg Rate of 4.54 is healthy, but the "Trips Count by Driver Rating" histogram shows a tail of lower ratings (below 4.0) that require investigation.

- Geospatial Gaps: The "Bottom 15 Avg Rate Areas" map identifies specific clusters in North America and Europe where driver ratings are underperforming the global average.

- Passenger Trends: The Sum of Passenger Count by Month reveals a sharp seasonal decline in August, suggesting a need for promotional campaigns during late summer.

## Recommendations Based on Analysis
- Optimize Low-Rate Areas: Investigate the "Bottom 15 Avg Rate Areas" to determine if low ratings are due to traffic congestion, driver availability, or regional pricing.

- Targeted Marketing: Increase driver incentives on Tuesdays, which currently show the lowest trip volume and fare.

- August Recovery: Since August shows the lowest passenger count, implement "Back to School" or summer-end discounts to flatten the seasonal dip.

