# nepal_flood_2026
the major Nepal flood disaster occurs in 2026 based on the official data by government of Nepal
### Nepal Flood Analysis Dashboard 🌧️🌊

An interactive Power BI dashboard designed to analyze flood patterns, assess socio-economic impact, and streamline disaster response efforts across different provinces and districts in Nepal. 

### 🔗 Live Project Links

* **Live Interactive Dashboard:** [Insert Power BI Publish to Web Link Here]
* **Dataset Source:** [Insert Data Source Link here, e.g., Nepal Disaster Risk Reduction Portal / Humanitarian Data Exchange]

### 📌 Project Overview & Problem Statement

In recent years, monsoon-driven floods in Nepal have caused severe damage to infrastructure, displaced thousands of families, and disrupted local economies—particularly in low-lying regions like the Terai plains. 

This project was built to transform raw disaster logs into actionable insights. The dashboard provides government agencies, NGOs, and rescue teams with a clear, data-driven view of: 

1. **Historical Trends:** Identifying high-risk months and shifting rainfall patterns.
2. **Geospatial Hotspots:** Pinpointing the most heavily impacted districts and provinces.
3. **Impact Assessment:** Quantifying human casualties, infrastructure damage, and financial losses to help optimize relief fund distribution.

### 📊 Key Insights & Features

* **Dynamic Risk Mapping:** A geospatial visual showing flood intensity, allowing users to drill down from the Province level to specific Districts and Municipalities.
* **Casualty & Displacement Tracker:** Real-time metrics showing total affected populations, injuries, and fatalities categorized by demographic splits (where available).
* **Economic Loss Matrix:** A breakdown of property, agricultural land, and livestock damages to evaluate the financial toll per region.
* **Historical Timeline Analysis:** An interactive time-series chart mapping flood frequencies over the last [X] years to identify seasonal anomalies.

### 🛠️ Tech Stack & Skills Demonstrated

* **Data Extraction & Cleaning:** Power Query (ETL) used to handle missing values, standardize district names (handling variations in English/Nepali transliteration), and merge climate data with census population data.
* **Data Modelling:** Star Schema architecture connecting a central Fact_Flood_Events table to localized dimension tables (Dim_Geography, Dim_Date, Dim_Impact_Severity).
* **DAX (Data Analysis Expressions):** Created advanced measures for rolling averages, year-over-year (YoY) impact growth, and dynamic severity ranking scores.
* **Data Visualization:** Power BI Desktop using custom tooltips, conditional formatting (color-coded risk tiers), and bookmarks for seamless navigation.

### 📸 Dashboard Preview

Here is a visual preview of the core analytical views: 

### 1. Main Summary & Executive Overview

 

### 2. Regional Risk & Vulnerability Mapping

 

*(Note: To add screenshots, create a folder named screenshots in your GitHub repository, upload your images there, and update the URLs above).* 

### 📈 Future Enhancements

* Integrate a live API feed from the Department of Hydrology and Meteorology (DHM) for real-time water level alerts.
* Incorporate machine learning predictive models (Python/R integration) to forecast potential flash flood boundaries based on real-time rainfall data.

### 🧑‍💻 How to Run the Project Locally

1. Clone this repository: 

bash

git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git

Use code with caution.
2. Ensure you have **Power BI Desktop** installed.
3. Open the [Your_File_Name].pbix file.
4. If prompted to refresh data sources, point the file pathway to the raw data files stored in the /data folder of this repository.

### 🤝 Contact & Connect

* **Author:** [Sanjeev kumar]
* **Email:** [sanjeevchintala111@gmail.com]
