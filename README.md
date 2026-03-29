# GDP and Immigration Dashboard (Power BI)

## Table of Contents

* [Project Overview](#project-overview)
* [Tools & Technologies](#tools--technologies)
* [Data Sources](#data-sources)
* [Data Cleaning/Preparation](#data-cleaningpreparation)
* [Dashboard Features](#dashboard-features)
  * [1. GDP Analysis](#1-gdp-analysis)
  * [2. Sector Analysis](#2-sector-analysis)
  * [3. Immigration Analysis](#3-immigration-analysis)
  * [4. Immigrant Demographic Insights](#4-immigrant-demographic-insights)
  * [5. Forecasting](#5-forecasting)
* [Key Insights](#key-insights)
* [What I Learned](#what-i-learned)


## Project Overview

This project presents an interactive Power BI dashboard analyzing the relationship between economic performance (GDP) and immigration patterns across countries and regions.

The dashboard enables users to explore:

* GDP trends over time
* Sectoral composition of economies
* Immigration inflows and demographics
* Forecasted migration patterns


## Tools & Technologies

* Power BI (Data visualization & dashboard)
* Power Query (Data transformation)
* DAX (Measures and calculations)


## Data Sources

The project uses multiple datasets from the [World Bank Group](https://data.worldbank.org/country) related to:

* GDP indicators (market price, GDP per capita)
* GDP by sector (agriculture, industry, services)
* Immigration inflows by country and region
* Demographic and education data of immigrants
* Country population
* Country region and income group



## Data Cleaning/Preparation
In Power Query:
* Renamed columns to appropriate descriptors (e.g., `Indicator Name` --> `GDP Type`)
* Removed empty columns and rows with missing values
* Reformatted GDP values (e.g., `3248134606.77511` --> `$3,248,134,606.78`)

In Power BI:
* Created **Country** and **Year** dimension tables
* Established relationships between tables



## Dashboard Features

### 1. GDP Analysis

* Highest and lowest GDP countries
* GDP trends over time
* Regional and income group comparisons
  <img width="1422" height="801" alt="image" src="https://github.com/user-attachments/assets/cc2567ad-4d13-44ab-b9a5-b36d9d843b44" />

  
### 2. Sector Analysis

* GDP composition (Agriculture, Industry, Services)
* Structural economic changes over time
* Average GDP sector percentage for different countries
  <img width="1424" height="800" alt="image" src="https://github.com/user-attachments/assets/68de1f30-9c35-48af-a3d0-1160b99963b2" />


### 3. Immigration Analysis

* Immigration inflows by country
* Origin and destination analysis
* Trends over time
  <img width="1429" height="802" alt="image" src="https://github.com/user-attachments/assets/ccb95b04-dab3-4922-b2b1-2b1e31d830f4" />


### 4. Immigrant Demographic Insights

* Education levels of immigrants
* Occupation distribution
* Gender comparison
  <img width="1426" height="804" alt="image" src="https://github.com/user-attachments/assets/587f89b5-bf99-485e-bd5b-51c97412399a" />


### 5. Forecasting

* Predicted immigration inflows
* Future workforce trends
  <img width="1427" height="803" alt="image" src="https://github.com/user-attachments/assets/78ea18fb-b477-42bb-b1b3-b5b45ddbdb38" />


## Key Insights

* High-income countries attract more immigrants
* Service sector dominates developed economies
* Migration trends correlate with economic performance
* Increasing proportion of skilled migrants over time
* Regional disparities highlight uneven economic development



## What I Learned

* Designing user-friendly dashboards
* Choosing appropriate visualizations for different data types
* Data storytelling and insight generation
* Handling messy real-world datasets

