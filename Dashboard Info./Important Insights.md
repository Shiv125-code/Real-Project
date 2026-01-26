* AQI Analysis Dashboard – Documentation

 1. Project Objective
The objective of this project is to analyze **Air Quality Index (AQI)** data across Indian states and cities and present meaningful insights through an interactive Power BI dashboard. 
The dashboard helps identify pollution severity, regional differences, seasonal trends, and dominant pollutants affecting air quality.

---
 2. Business / Analytical Problem
Raw air quality data is difficult to interpret due to its volume and complexity. Without proper analysis, it is challenging to:
- Identify the most polluted regions
- Understand seasonal pollution patterns
- Determine key pollutants contributing to poor air quality

This project addresses these challenges by transforming raw AQI data into clear, visual, and decision-ready insights.

---
3. Data Overview
The dataset contains daily air quality measurements with the following key fields:
- Date
- State
- City / Area
- AQI Value
- Air Quality Status
- Prominent Pollutants
- Number of Monitoring Stations

---
4. Data Cleaning & Preparation
Data preparation was performed using *Power Query*:
- Removed missing and inconsistent values
- Standardized column names and data types
- Created derived columns for analysis
- Ensured data consistency for accurate filtering and aggregation

This step ensured the dataset was reliable and ready for analysis.

---
 5. Data Modeling
- Built optimized relationships between date, region, and AQI tables
- Ensured correct filter propagation across visuals
- Structured the data model to support time-series and regional analysis

A clean data model improved dashboard performance and usability.

---
6. DAX Calculations & Logic

* AQI Classification
AQI values were categorized using a calculated column with `SWITCH(TRUE())` logic:
- Good
- Moderate
- Poor
- Unhealthy
- Very Unhealthy
- Hazardous

*KPI Measures
Created DAX measures to calculate:
- Average AQI
- Maximum AQI
- AQI Category (based on value ranges)

* Ranking Logic
Used ranking functions to identify:
- Top 10 most polluted cities and regions

* Pollutant Analysis
Built frequency-based DAX logic to determine:
- Primary (dominant) pollutants contributing to air pollution

---
7. Dashboard Components

/Key Visuals
-KPI Cards:  Display average AQI, maximum AQI, and air quality status
- Line Chart:  Monthly AQI trend analysis
- Bar Chart:    Top 10 most polluted cities
- Donut Chart:   AQI category distribution
- Bar Chart:  Pollutant frequency analysis

* Interactivity
- Slicers for Year, State, City, and Month
- Enables detailed drill-down and comparative analysis

---

8. Key Insights
- PM2.5 and PM10 are the most dominant pollutants across multiple regions
- AQI levels show clear seasonal variation
- Certain urban areas consistently record higher AQI values
- Majority of observations fall under Moderate and Poor AQI categories

---

9. Analytical Value
- Enables region-wise and time-based air quality comparison
- Supports data-driven environmental assessment
- Helps identify high-risk pollution zones
- Demonstrates real-world data analytics and BI workflow

---

10. Skills Demonstrated
- Data Cleaning & Transformation (ETL)
- Exploratory Data Analysis (EDA)
- Data Modeling
- DAX Calculations
- KPI Development
- Data Visualization
- Dashboard Storytelling
- Business Intelligence Reporting

---

11. Conclusion
This project demonstrates an **end-to-end data analytics solution**, from raw data preparation to insight-driven visualization. 
It highlights strong analytical thinking, Power BI expertise, and the ability to communicate complex environmental data in a clear and impactful manner.
