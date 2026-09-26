# Agricultural Climate & Crop Yield Analysis

**An end-to-end Data Analytics and Business Intelligence project analyzing climate and crop yield data using AWS S3, Snowflake, Power Query, and Power BI.**

---

## Project Overview

**Agricultural Climate & Crop Yield Analysis** is an end-to-end Data Analytics and Business Intelligence project that analyzes agricultural and climatic data across multiple years, seasons, crops, and geographic locations.

The project follows a complete analytics workflow: data is stored in **AWS S3**, warehoused in **Snowflake**, cleaned and transformed using **Power Query**, and modeled and visualized in **Microsoft Power BI** using **DAX** measures.

### Key Areas Analyzed

| Climate | Agriculture | Geography |
|---|---|---|
| Temperature | Crop Yield | Location |
| Humidity | Crop Performance | Region |
| Rainfall | Seasonal Productivity | Year |
| Seasonal Conditions | Agricultural Trends | Season |

---

## Project Objectives

- Analyze temperature patterns across years and locations
- Analyze humidity variations across seasons, crops, and locations
- Understand rainfall patterns across years and regions
- Compare crop yield across different crops
- Analyze agricultural productivity across locations
- Compare agricultural conditions across seasons
- Identify variations in agricultural and climatic metrics
- Build interactive, insight-driven Power BI dashboards
- Implement an end-to-end cloud-to-BI analytics workflow

---

## Technology Stack

| Technology | Role in Project |
|---|---|
| AWS S3 | Cloud-based storage for the source dataset |
| Snowflake | Cloud data warehouse and analytical data layer |
| Power Query | Data cleaning and transformation |
| Microsoft Power BI | Data visualization and dashboard development |
| DAX | Analytical calculations and measures |
| Power BI Data Modeling | Structuring data for analytical reporting |

---

## Data Pipeline

### AWS S3 — Cloud Storage

Used as the cloud storage layer of the project.

- Uploaded the agricultural dataset to an AWS S3 bucket
- Used S3 as a centralized cloud storage location
- Incorporated cloud storage into the end-to-end analytics workflow
- Prepared the dataset for downstream processing

### Snowflake — Data Warehouse

Used as the cloud data warehouse for storing and managing analytical data.

- Loaded agricultural data into Snowflake
- Stored structured analytical data
- Worked with data at the warehouse layer
- Prepared data for analytical consumption through Power BI

### Power Query — Data Cleaning & Transformation

Used to prepare the dataset before visualization.

- Removed unnecessary data
- Handled missing or inconsistent values
- Changed data types where required
- Renamed and organized columns
- Transformed data into an analysis-ready format

**Transformation workflow:**
Raw Data → Data Inspection → Remove Unnecessary Data → Handle Missing/Inconsistent Values
→ Change Data Types → Rename Columns → Transform Data → Load into Power BI Model
→ Create DAX Measures → Build Visualizations

---

## Power BI Dashboards

Four interactive dashboards were built, each analyzing a key metric across **Year, Season, Crop, and Location**.

| Metric | Analysis Dimensions |
|---|---|
| Average Humidity | Year • Season • Crop • Location |
| Average Temperature | Year • Season • Crop • Location |
| Average Rainfall | Year • Season • Crop • Location |
| Average Yield | Year • Season • Crop • Location |

### 1. Humidity Analysis

Examines average humidity across different agricultural dimensions.

**Visualizations:** Average Humidity by Year, Season, Crop, and Location

![Humidity Analysis Dashboard](https://github.com/user-attachments/assets/6c123086-6385-44ce-8184-1878aa376c2d)

### 2. Temperature Analysis

Analyzes average temperature across different dimensions.

**Visualizations:** Average Temperature by Year, Season, Crop, and Location

![Temperature Analysis Dashboard](https://github.com/user-attachments/assets/5595c134-fd09-40af-842a-10c755b96f76)

### 3. Rainfall Analysis

Focuses on rainfall patterns across agricultural dimensions.

**Visualizations:** Average Rainfall by Year, Season, Crop, and Location

![Rainfall Analysis Dashboard](https://github.com/user-attachments/assets/0ce46a6d-be8b-4f77-bbcc-571af4360955)

### 4. Yield Analysis

Focuses on agricultural productivity and crop yield.

**Visualizations:** Average Yield by Year, Season, Crop, and Location

![Yield Analysis Dashboard](https://github.com/user-attachments/assets/e77dd990-3e35-473a-9b2f-6b239c0306b4)

---

## DAX & Analytical Calculations

DAX was used within Power BI to create the measures powering each dashboard, including:

- Average calculations and aggregations
- Category-level analysis
- Year-wise, season-wise, crop-wise, and location-wise analysis

## Data Visualization Techniques

- Horizontal bar charts
- Category comparisons (year, season, crop, location)
- Data labels for precise reading
- Interactive, dashboard-based storytelling

## Data Modeling

- Structured the dataset for analysis
- Prepared fields for visualization
- Created analytical measures
- Organized categorical and numerical fields
- Modeled data for year, season, crop, and location analysis

---

## Key Analytical Questions

**Climate Analysis**
- How does average temperature vary across years?
- How does humidity vary across different locations?
- Which seasons have higher average temperature?
- How does rainfall vary across different years?
- Which locations receive higher average rainfall?
- How do climatic conditions vary across seasons?

**Crop Analysis**
- Which crops have higher average yield?
- How does crop yield vary across locations?
- How does agricultural productivity vary across seasons?
- How does yield vary across different years?
- How do rainfall conditions vary across crops?
- How do climate-related metrics vary across crops?

---

## Scope of Data

**Locations analyzed:** Bangalore, Mysuru, Mangalore, Hassan, Kodagu, Raichur, Gulbarga, Madikeri, Chikkamagaluru, Kasaragodu, Davangere

**Crops analyzed:** Cotton, Coconut, Ginger, Tea, Blackgram, Coffee, Pepper, Paddy, Groundnut, Arecanut, Cardamom, Cashew, Cocoa

> **Note:** The dashboards are designed for exploratory analysis. Individual visual values should be interpreted according to the underlying dataset and its measurement units.

---

## Learning Outcomes

- **Cloud Technologies:** AWS S3, cloud-based data storage and workflows
- **Data Warehousing:** Snowflake, data loading, structured analytical data management
- **Data Preparation:** Power Query, data cleaning, transformation, and type management
- **Business Intelligence:** Power BI, data modeling, dashboard development, interactive visualizations
- **Analytical Skills:** DAX, aggregations, KPI-oriented analysis across year, season, crop, and location

---

## Skills Demonstrated

AWS S3 • Snowflake • Power BI • Power Query • DAX • Data Cleaning • Data Transformation • Data Modeling • Data Visualization • Business Intelligence • Data Analysis • Dashboard Development • Cloud Data Analytics • Data Warehousing

---

---

## Project Workflow
AWS S3 → Snowflake → Power Query → Data Cleaning & Transformation
→ Power BI Data Model → DAX Measures → Interactive Dashboards
→ Agricultural & Climate Analysis


---

## Conclusion

This project demonstrates a complete end-to-end data analytics workflow:

**Cloud Storage → Data Warehousing → Data Transformation → Data Modeling → DAX → Business Intelligence**

The combination of AWS S3, Snowflake, Power Query, DAX, and Power BI provided hands-on experience in handling data from the storage layer through to the final analytical dashboard. The resulting dashboards offer an interactive way to explore humidity, temperature, rainfall, and crop yield across different years, seasons, crops, and locations.

---

## About Me

**Karthik T**
B.Tech — Artificial Intelligence & Machine Learning

**Areas of Interest:** Data Analytics, Business Intelligence, Data Visualization, Machine Learning, Cloud Data Technologies

**Technical Skills:** Python, SQL, Power BI, Excel, Pandas, NumPy, Power Query, DAX, AWS S3, Snowflake, Data Analysis, Data Visualization

**Connect:**
[LinkedIn](https://www.linkedin.com/in/karthik-t-932564369) · [GitHub](https://github.com/karthikkarthi18012008-star)

---

If you found this project useful, consider giving the repository a star.
