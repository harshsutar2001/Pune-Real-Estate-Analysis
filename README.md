# Pune-Real-Estate-Analysis



A complete end‑to‑end project analyzing Pune real estate data using **Excel**, **Python (EDA)**, and **Power BI**. This repository provides a clean workflow from raw data → cleaned dataset → visual insights → business‑ready dashboards.

---

## 1. Project Overview

This project aims to understand real-estate trends in Pune by analyzing property characteristics such as **area**, **square feet**, **bedrooms**, **bathrooms**, **amenities**, and **price**.

### Main Goals

* Clean and prepare property data for analysis
* Generate new calculated columns
* Identify pricing patterns and trends
* Understand how features affect property prices
* Build interactive dashboards for decision-making

---

## 2. Business Problem

Real estate prices in Pune vary widely depending on **location**, **property size**, **age**, and **amenities**. Homebuyers, investors, and developers need insights such as:

* Which areas are most expensive?
* How much does square footage influence price?
* Do amenities like swimming pools and gardens impact pricing?
* Which properties have the best value per square foot?

This project answers these questions using real data and modern analytics tools.

---

## 3. Dataset Columns

* **id** – Unique property identifier
* **area** – Locality/region in Pune
* **square_feet** – Size of the property
* **num_bedrooms** – Number of bedrooms
* **num_bathrooms** – Number of bathrooms
* **year_built** – Construction year
* **has_garage** – Garage availability
* **price** – Total property price
* **age** – *Calculated: current year – year_built*
* **price_per_sqrt** – *Calculated: price / square_feet*
* **swimming_pool** – Amenity indicator
* **garden** – Amenity indicator

---

## 4. Tools Used

### Excel

* Initial data cleaning
* Removing duplicates
* Correcting data types
* Adding calculated columns

### Python (Jupyter Notebook)

* In-depth Exploratory Data Analysis
* Statistical summaries
* Visualizations

### Power BI

* KPI cards
* Interactive dashboards
* Geo and heatmap visuals
* Slicers for filtering

---

## 5. Excel Work (Detailed)

* Clean text fields (trim, proper case)
* Standardize column names
* Remove duplicates using ID or property combination
* Convert numeric fields (price, square_feet) correctly
* Add calculated columns:

  * Age
  * Price per sq ft
* Flag missing values and outliers
* Export cleaned dataset for Python & Power BI

---

## 6. Python EDA (Detailed)

### Key Analyses

* **Distribution of Price** – understand price spread
* **Price vs Square Feet** – relationship between size and cost
* **Avg Price by Area** – locality-wise comparison
* **Correlation Heatmap** – identify strong influencers of price
* **Categorical Analysis** – bedrooms, bathrooms, amenities

### Insights from EDA (examples)

* Larger homes show a strong positive correlation with higher prices
* Prime areas have high price per sq ft
* Newer properties are generally more expensive
* Homes with swimming pools show premium pricing

---

## 7. Power BI Dashboard (Expanded)

### KPIs

* **Average Price**
* **Average Price per Sq Ft**
* **Total Properties**
* **New Listings** (if applicable)

### Dashboard Visuals

* **Bar Chart:** Avg price by area
* **Map View:** Area-wise price distribution
* **Scatter Plot:** Square feet vs price
* **Heatmap:** Swimming pool availability vs area
* **Matrix:** Bedrooms vs bathrooms
* **Line Chart:** Avg price by age of property

### Filters / Slicers

* Area
* Bedrooms
* Price range
* Amenities (pool, garden)

---

## 8. Repository Structure

```
pune-real-estate-analysis/
│── data/                 # raw and cleaned data
│── excel/                # Excel cleaning files
│── notebooks/            # Jupyter notebooks for EDA
│── power_bi/             # PBIX and details
│── reports/              # insights and screenshots
│── README.md
```

---

## 9. Insights Summary

Some common insights the project highlights:

* Premium areas in Pune show significantly higher avg prices
* Square footage strongly impacts overall price
* Amenities like pools and gardens add noticeable value
* Older properties generally cost less
* Price per sq ft helps compare properties fairly across areas

---

## 10. Conclusion

This project provides a complete workflow from data cleaning to visual insights, helping users understand Pune's real-estate market and make informed decisions.

---


