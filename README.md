# Airbnb Data Analysis & Interactive Tableau Dashboard

## Project Overview
This project presents an exploratory data analysis (EDA) of 2016 Airbnb listing data using **Tableau**, focusing on pricing behavior, availability patterns, property characteristics, and geographic distribution.

The original Airbnb dataset can be accessed here:  
[InsideAirBnb](https://insideairbnb.com/get-the-data/)
 
##  Live Dashboard
Access the interactive Tableau dashboard on Tableau Public:  

https://public.tableau.com/app/profile/yonatan.verch/viz/AirBnbFullProject_17675944230570/Dashboard1

##  Repository Contents
- `AirBnb Full Project.twb` – Tableau workbook containing dashboards, calculated fields, and filters  
- `Tableau Full Project.xlsx` – Dataset used for analysis

##  Tools & Technologies
- **Tableau** – Interactive dashboards and visual analytics  
- **Microsoft Excel** – Data storage and preprocessing
- 
## Dashboard Screenshots

### Full Dashboard Overview
![Dashboard Overview](images/dashboard_overview.png)

This view provides a high-level summary of Airbnb listings, highlighting pricing patterns, availability trends, and geographic distribution across neighborhoods.

---

### Pricing Analysis
![Pricing Trends](images/pricing_trends.png)

This visualization explores nightly price distributions and trends, revealing a right-skewed distribution driven by premium listings and neighborhood-level variation.

---

### Neighborhood Distribution
![Neighborhood Map](images/neighborhood_map.png)

A geographic view of Airbnb listings showing strong concentration in central, high-demand neighborhoods with higher average prices.

## Key Analytical Findings

 **Dataset scope:**  
  Analysis includes **3,818 Airbnb listings** with pricing, availability, room type, and location attributes.

- **Pricing distribution:**  
  - **Average nightly price:** ~$128  
  - **Median nightly price:** ~$100  
  The gap between mean and median indicates a **right-skewed distribution**, driven by higher-priced premium listings.

- **Room type composition:**  
  - **Entire home/apartment:** ~66.6% of listings  
  - **Private room:** ~30.4%  
  - **Shared room:** ~3.0%  
  Entire homes account for the majority of listings and dominate the higher price ranges.

- **Availability patterns:**  
  - **Average availability:** ~245 days per year  
  This suggests a mix of full-time rental properties and short-term or seasonal listings.

- **Price vs. availability relationship:**  
  Higher-priced listings generally exhibit **lower availability**, consistent with demand-driven and premium pricing behavior.

- **Geographic concentration:**  
  Listings are highly concentrated in central, high-demand neighborhoods, where **average prices are noticeably higher** than in peripheral areas.
  
## How to Use This Project
1. Download the Tableau workbook (`.twb`) and dataset file  
2. Open the workbook in **Tableau Desktop**  
3. Ensure the Excel file is located in the same directory as the workbook  
4. Use interactive filters, maps, and charts to explore trends by neighborhood, room type, price range, and availability
