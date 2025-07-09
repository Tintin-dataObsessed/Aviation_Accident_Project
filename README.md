# ✈️ Aviation Accident Analysis Project

This project analyzes aviation accident data from **1962 to 2023, focusing on civil aviation accidents and selected incidents in the United States and international waters**. The goal is to identify patterns, assess risk levels by aircraft type, and provide actionable recommendations for safer investments in aircraft models.

---

## Business Understanding

The objective of this analysis is to help stakeholders identify the lowest-risk aircraft based on historical accident and incident data. By breaking down and analyzing the data, the project aims to support data-driven decisions for those looking to purchase or invest in aircraft.

---

## Data Understanding

The data comes from the **Aviation Accident Database & Synopses (up to 2023)**. It includes detailed records of aviation accidents and incidents.

**Steps taken to understand the data:**
- Used `.describe()` to generate basic descriptive statistics
- Used `.info()` to review data structure and types
- Summarized the contents and highlighted key limitations, including missing values and incomplete categories

---

## Data Preparation

The dataset was cleaned using the following steps:

- **Missing values**: Numerical columns with missing values were filled using mean imputation; less impactful rows with missing data were dropped
- **Duplicates**: Identified and removed using the unique Event ID
- **Categorical formatting**: Standardized text columns to lowercase for consistency
- Preserved valuable missing indicators with `NaN` values where appropriate

---

## Data Analysis

### 1. Make and Model Risk Assessment
- Analyzed accidents and incidents by aircraft make and model
- Identified least accident-prone and least injury-prone models
- Recommended aircraft based on low accident and injury rates

### 2. Fatal Injuries by Aircraft Category
- Grouped aircraft by on-air category
- Visualized fatal injury data to find categories with the highest and lowest fatality rates
- Created supporting charts and tables

### 3. Airplanes Focused Analysis
- Filtered data specifically for airplanes
- Although airplanes had the highest number of incidents, filtering for low injuries, minor damage, and minimal fatalities revealed a list of safe airplane models

---

## Dashboard

The final dashboard was created using **Tableau** to visualize insights in an interactive way.

🔗 [View the Tableau Dashboard](https://public.tableau.com/views/Accident_Aviation/Dashboard4?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)




