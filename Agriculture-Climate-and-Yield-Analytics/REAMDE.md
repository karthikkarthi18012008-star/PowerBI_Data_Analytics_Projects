# 🌾 Agricultural Climate & Crop Yield Analysis

### AWS S3 • Snowflake • Power Query • Power BI • DAX

An end-to-end **Data Analytics and Business Intelligence project** focused on analyzing agricultural and climatic data across different **years, seasons, crops, and locations**.

The project demonstrates a complete data pipeline starting from **cloud-based data storage using AWS S3**, followed by **data warehousing using Snowflake**, data cleaning and transformation using **Power Query**, and finally analytical modeling and interactive visualization using **Microsoft Power BI**.

---

## 📌 Project Overview

Agricultural productivity is influenced by several environmental factors such as **temperature, humidity, rainfall, and seasonal conditions**.

This project analyzes these factors along with **crop yield** to understand variations across different years, seasons, crops, and geographical locations.

The final Power BI solution consists of four analytical dashboards:

- 💧 Humidity Analysis
- 🌡️ Temperature Analysis
- 🌧️ Rainfall Analysis
- 🌾 Yield Analysis

The project focuses on transforming raw agricultural data into meaningful and interactive visual insights.

---

# 🎯 Project Objectives

The main objectives of this project are:

- Analyze temperature patterns across different years.
- Analyze humidity variations across seasons and locations.
- Understand rainfall patterns across different years and regions.
- Compare agricultural yield across different crops.
- Analyze crop productivity across locations.
- Compare agricultural conditions across different seasons.
- Identify variations in agricultural and climatic metrics.
- Build interactive and visually appealing Power BI dashboards.
- Implement an end-to-end cloud-to-BI analytics workflow.

---



| Technology            | Purpose                                                       |
| --------------------- | ------------------------------------------------------------- |
| ☁️ AWS S3             | Cloud-based storage for the source dataset                    |
| ❄️ Snowflake          | Cloud data warehouse for storing and managing analytical data |
| 📊 Microsoft Power BI | Data visualization and dashboard development                  |
| 🔄 Power Query        | Data cleaning and transformation                              |
| 📐 DAX                | Analytical calculations and Power BI measures                 |
| 🧩 Data Modeling      | Structuring data for analytical reporting                     |


☁️ ##AWS S3

AWS S3 was used as the cloud storage layer of the project.

Activities Performed
Uploaded the source agricultural dataset to an S3 bucket.
Used S3 as a centralized cloud storage location.
Incorporated cloud storage into the end-to-end analytics workflow.
Prepared the dataset for downstream data processing.

❄️ ##Snowflake

Snowflake was used as the cloud data warehouse.

Activities Performed
Loaded agricultural data into Snowflake.
Stored structured analytical data.
Worked with data at the warehouse layer.
Prepared data for analytical consumption through Power BI.
Used Snowflake as the data warehousing component of the pipeline.

🔄 ##Power Query

Power Query Editor was used extensively for data cleaning and transformation.

Data Preparation Activities
Removed unnecessary data.
Handled missing or inconsistent values.
Changed data types where required.
Renamed and organized columns.
Transformed data into an analysis-ready format.
Prepared data for Power BI modeling.
Applied required transformations before visualization.

📊 ##Power BI

Microsoft Power BI was used to develop the final Business Intelligence dashboards.

The dashboards provide analysis across:

Year
Season
Crop
Location

The major metrics analyzed include:

Average Humidity
Average Temperature
Average Rainfall
Average Yield
💧 1. Humidity Analysis
<img width="1348" height="731" alt="Screenshot 2026-09-26 195605" src="https://github.com/user-attachments/assets/6c123086-6385-44ce-8184-1878aa376c2d" />

The Humidity Analysis dashboard examines average humidity across different dimensions.

Visualizations
Average Humidity by Year
Average Humidity by Season
Average Humidity by Crops
Average Humidity by Location
Analysis

This dashboard helps understand how humidity levels vary across different agricultural conditions, seasons, crops, and geographical locations.

Dashboard Preview

🌡️ 2. Temperature Analysis
<img width="1335" height="736" alt="Screenshot 2026-09-26 195535" src="https://github.com/user-attachments/assets/5595c134-fd09-40af-842a-10c755b96f76" />

The Temperature Analysis dashboard analyzes average temperature across different dimensions.

Visualizations
Average Temperature by Year
Average Temperature by Season
Average Temperature by Crops
Average Temperature by Location
Analysis

This dashboard provides an overview of temperature variations across different years, seasons, crops, and locations.

Dashboard Preview

🌧️ 3. Rainfall Analysis
<img width="1347" height="738" alt="Screenshot 2026-09-26 195432" src="https://github.com/user-attachments/assets/0ce46a6d-be8b-4f77-bbcc-571af4360955" />

The Rainfall Analysis dashboard focuses on rainfall patterns across different agricultural dimensions.

Visualizations
Average Rainfall by Year
Average Rainfall by Season
Average Rainfall by Crops
Average Rainfall by Location
Analysis

This dashboard allows users to compare rainfall patterns across years, seasons, crops, and geographical locations.

Dashboard Preview

🌾 4. Yield Analysis
<img width="1333" height="737" alt="Screenshot 2026-09-26 195415" src="https://github.com/user-attachments/assets/e77dd990-3e35-473a-9b2f-6b239c0306b4" />

The Yield Analysis dashboard focuses on agricultural productivity.

Visualizations
Average Yield by Year
Average Yield by Season
Average Yield by Crops
Average Yield by Location
Analysis

This dashboard helps compare crop productivity across different crops, seasons, years, and locations.

Dashboard Preview

📈 Dashboard Metrics

The project analyzes the following major metrics:

Metric	Analysis Dimensions
💧 Average Humidity	Year, Season, Crop, Location
🌡️ Average Temperature	Year, Season, Crop, Location
🌧️ Average Rainfall	Year, Season, Crop, Location
🌾 Average Yield	Year, Season, Crop, Location
🧮 DAX & Analytical Calculations

DAX was used within Power BI to create analytical measures and perform calculations required for the dashboards.

The analysis includes:

Average calculations
Aggregations
Category-level analysis
Year-wise analysis
Season-wise analysis
Crop-wise analysis
Location-wise analysis

These calculations were used to support the interactive Power BI visualizations.

🔍 Key Analytical Questions

The dashboard can be used to answer questions such as:

Climate Analysis
How does average temperature vary across years?
How does humidity vary across different locations?
Which seasons have higher average temperature?
How does rainfall vary across different years?
Which locations receive higher average rainfall?
How do climatic conditions vary across different seasons?
Crop Analysis
Which crops have higher average yield?
How does crop yield vary across locations?
How does agricultural productivity vary across seasons?
How does yield vary across different years?
Which crops experience different rainfall conditions?
How do climate-related metrics vary across crops?
📍 Locations Analyzed

The dashboard includes analysis across multiple locations, including:

Bangalore
Mysuru
Mangalore
Hassan
Kodagu
Raichur
Gulbarga
Madikeri
Chikkamagaluru
Kasaragodu
Davangere
🌾 Crops Analyzed

The dashboard contains crop-level analysis for crops including:

Cotton
Coconut
Ginger
Tea
Blackgram
Coffee
Pepper
Paddy
Groundnut
Arecanut
Cardamom
Cashew
Cocoa
📊 Data Visualization Techniques

The project uses Power BI visualizations to make the analysis easy to understand.

Visualization Techniques Used
Horizontal bar charts
Category comparisons
Year-wise trend analysis
Season-wise comparisons
Crop-wise comparisons
Location-wise comparisons
Data labels
Dashboard-based analytical storytelling
🧹 Data Cleaning & Transformation

Before building the dashboards, the data was prepared using Power Query.

Transformation Workflow
Raw Data
   ↓
Data Inspection
   ↓
Remove Unnecessary Data
   ↓
Handle Missing / Inconsistent Values
   ↓
Change Data Types
   ↓
Rename Columns
   ↓
Transform Data
   ↓
Load into Power BI Model
   ↓
Create Measures
   ↓
Build Visualizations
🧠 Data Modeling

The Power BI data model was prepared to support analytical reporting.

The modeling process included:

Structuring the dataset for analysis
Preparing fields for visualization
Creating analytical measures
Organizing categorical and numerical fields
Preparing data for year, season, crop, and location analysis
💡 Key Insights Supported by the Dashboard

The dashboard enables users to explore:

Year-wise changes in climatic conditions.
Seasonal variations in temperature, humidity, and rainfall.
Differences in climate metrics between locations.
Crop-wise differences in agricultural productivity.
Location-wise differences in yield.
Relationships between agricultural output and environmental conditions.

Note: The dashboard is designed for exploratory analysis. Individual visual values should be interpreted according to the underlying dataset and its measurement units.

🎓 Learning Outcomes

Through this project, I gained practical experience in:

Cloud Technologies
AWS S3
Cloud-based data storage
Cloud data workflow
Data Warehousing
Snowflake
Data loading
Structured analytical data management
Data Preparation
Power Query
Data cleaning
Data transformation
Data type management
Business Intelligence
Power BI
Data modeling
Dashboard development
Interactive visualizations
Analytical Skills
DAX
Aggregations
KPI-oriented analysis
Year-wise analysis
Season-wise analysis
Crop-wise analysis
Location-wise analysis
🚀 Skills Demonstrated
AWS S3
Snowflake
Power BI
Power Query
DAX
Data Cleaning
Data Transformation
Data Modeling
Data Visualization
Business Intelligence
Data Analysis
Dashboard Development
Cloud Data Analytics
Data Warehousing
Analytical Reporting
📁 Project Structure
Agricultural-Climate-PowerBI/
│
├── README.md
│
├── Dataset/
│   └── agricultural_data.csv
│
├── PowerBI/
│   └── Agricultural_Climate_Analysis.pbix
│
├── screenshots/
│   ├── humidity-analysis.png
│   ├── temperature-analysis.png
│   ├── rainfall-analysis.png
│   └── yield-analysis.png
│
└── Documentation/
    └── project-documentation.md
🖼️ Dashboard Gallery
Humidity Analysis

Temperature Analysis

Rainfall Analysis

Yield Analysis

⭐ Project Highlights
☁️ Integrated AWS S3 into the data workflow
❄️ Used Snowflake as the data warehouse
🔄 Performed data cleaning and transformation using Power Query
📊 Developed Power BI dashboards
📐 Used DAX for analytical calculations
🌡️ Analyzed temperature patterns
💧 Analyzed humidity patterns
🌧️ Analyzed rainfall patterns
🌾 Analyzed crop yield
📍 Performed location-wise analysis
📅 Performed year-wise and season-wise analysis
📈 Built an end-to-end cloud-to-BI analytics workflow
🔗 Project Workflow Summary
AWS S3
  ↓
Snowflake
  ↓
Power Query
  ↓
Data Transformation
  ↓
Power BI Data Model
  ↓
DAX Measures
  ↓
Interactive Dashboards
  ↓
Agricultural & Climate Analysis
🏁 Conclusion

This project demonstrates a complete end-to-end data analytics workflow by combining cloud storage, cloud data warehousing, data transformation, analytical modeling, and business intelligence visualization.

The combination of AWS S3, Snowflake, Power Query, DAX, and Power BI provides practical experience in handling data from the storage layer through to the final analytical dashboard.

The resulting dashboards provide an interactive way to explore humidity, temperature, rainfall, and crop yield across different years, seasons, crops, and locations.

👨‍💻 Author
Karthik T

B.Tech — Artificial Intelligence & Machine Learning

Areas of Interest
Data Analytics
Business Intelligence
Data Visualization
Machine Learning
Cloud Data Technologies
Technical Skills
Python
SQL
Power BI
Excel
Pandas
NumPy
Power Query
DAX
AWS S3
Snowflake
Data Analysis
Data Visualization
