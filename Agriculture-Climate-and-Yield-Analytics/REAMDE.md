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
