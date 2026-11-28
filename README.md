# GeoPulse-Hyper-Local-Retail-Mobility-Analytics
GeoPulse: Hyper-Local Retail Mobility Analytics – A Data Analytics project focused on geographical retail patterns, customer mobility, location analysis, and interactive dashboards.


# Project Overview

GeoPulse is a Data Analytics project focused on understanding geographical retail patterns, customer mobility, and location-based business opportunities.

The project aims to collect, clean, analyze, and visualize data to identify retail trends, geographical patterns, and actionable business insights.


# Project Objectives

A.Collect and understand relevant datasets.

B.Clean and validate data using Python.

C.Perform Exploratory Data Analysis (EDA).

D.Analyze geographical and retail activity patterns.

E.Identify trends, hotspots, and business opportunities.

F.Create meaningful data visualizations.

G.Develop an interactive Power BI dashboard.

H.Present actionable business insights.

# Technologies & Tools

Python

Pandas

NumPy

Matplotlib

Seaborn

GeoPandas

Folium

Power BI

Google Colab

GitHub

# Upcoming Tasks

a- Data collection and validation.

b- Data cleaning and preprocessing.

c- Exploratory Data Analysis (EDA).

d- Geographical and retail mobility analysis.

e- Data visualization and dashboard development.

f- Business insights and recommendations.

g- Final project report and presentation.

# Expected Deliverables

Source Code

Project Documentation

Project Report

PowerPoint Presentation

Model Evaluation Results 

Final Project Demonstration 

### Today's Work – 13 November 2026

Today, I created a dedicated GitHub repository for my GeoPulse – Hyper-Local Retail Mobility Analytics project. I added the initial README.md file with the project overview, objectives, technologies and expected deliverables. I also created an organized folder structure for raw and processed datasets, Python notebooks, source code, charts, reports, dashboards and documentation. Additionally, I added a requirements.txt file containing the initial Python data science libraries needed for the project.

 **What I Learned:**
- How to create and manage a GitHub repository.
- How to organize a data analytics project professionally.
- The purpose of raw and processed datasets.
- How Git tracks project changes through commits.
- The importance of requirements.txt for managing Python dependencies.

 
 ### 14th November 2026
Completed work:
- Completed the initial GeoPulse GitHub repository setup.
- Added the requirements.txt file for project dependencies.
- Finalised Kolkata as the geographical study area.
- Selected Park Street and nearby areas: Camac Street, Middleton Row, and Free School Street.
- Defined the dataset structure for collecting business-location information

  
### 15th november 2026
  Worked on the GeoPulse Kolkata dataset in Google Colab. Loaded the collected GeoJSON file containing 347 geographical records and converted the data into a Pandas DataFrame. Inspected business details, coordinates and address information. Identified 7 potential duplicate records across 3 groups (Astoria Hotel, Cha Bar and Lenskart) and added duplicate-review flags without deleting any original records. Also identified missing street information in 269 records for further investigation. Learned about GeoJSON processing, data cleaning, duplicate detection and geographical data validation.
  
# What I learned
- How to load and inspect GeoJSON files using Python.
- How to convert geographical data into a Pandas DataFrame.
- How to extract latitude and longitude.
- How to identify potential duplicate business listings.
- Why missing address information and geographical search boundaries matter in spatial data analysis.

### 16th november 2026
  Worked on improving the quality of the GeoPulse Kolkata dataset. Added duplicate review flags using `duplicate_status` and `duplicate_group` columns while preserving all 347 original records. Identified 7 records across 3 potential duplicate groups for further investigation. Also reviewed the street-name standardisation report and identified entries requiring manual verification.

 # What I learned:
- Duplicate detection and data validation.
- Using Pandas to organise geographical data.
- Street-name standardisation.
- Identifying records that require manual verification.

### 18th november 2026
  Continued high-priority spatial analysis in GeoPulse. Checked distances between selected locations and nearby roads and compared the original street information with the nearest road results. Identified Acharya Jagadish Chandra Bose Road, Collin Street and Mirza Ghalib Street as nearby roads during the inspection. Completed the spatial review and exported the results as `GeoPulse_High_Priority_Spatial_Review.csv`. Started inspecting original OpenStreetMap records for verification.

  ### 19th november 2026
Continued GeoPulse spatial validation . Inspected original OpenStreetMap records for Red Arrow Residency, Taj Ladge and Desires. Verified their OSM IDs, addresses, coordinates, tags and record history. Compared the original source information with the spatial analysis results and updated the high-priority review report. All three records were verified, while unresolved discrepancies were retained for further investigation without applying any corrections.

### 20th november 2026
Continued working on GeoPulse by completing Steps 31–35. Prepared a spatial quality summary and an Excel assessment report for the selected high-priority locations. Performed a dataset health check on the original, working, business and roads datasets. Analysed the Shop, Amenity and Tourism categories and identified missing category values. Created a combined `main_category` column by applying a priority-based classification method. Successfully classified all 347 records into 57 categories with zero unclassified records and reviewed the combined category distribution.
# What I learned
- How to check dataset dimensions and data health.
- How to analyse business categories using Pandas.
- How to identify missing category information.
- How to understand OpenStreetMap tags such as shop, amenity and tourism.
- How to summarise geographical data for further analysis.

### 21st november 2026
Continued the GeoPulse project by completing next part. Analysed the combined business categories and created a horizontal bar chart showing the top 15 categories. The most frequent categories included restaurants (70), hotels (55) and fast food (42). Also created a donut chart showing the business category composition of Park Street, Kolkata, displaying the top five categories separately and grouping the remaining categories as Other categories. Added percentage labels and reviewed the completed visualisations.
# What I learned
1. How to identify the top business categories using Pandas.
2. How to create horizontal bar charts for category comparison.
3. How to create donut charts for category composition.
4. How to calculate and display percentage distributions.
5. How to communicate geographical business patterns through visualisation.

### 22nd november 2026
Continued working on GeoPulse by Created a business location and road network map using 347 OpenStreetMap location records and 325 road features. Saved the output as `GeoPulse_Business_Location_Road_Map.png`. Then created a colourful category-based map showing the top 8 business categories separately and grouping the remaining categories as Other categories. Compared the geographical distribution of different business types and saved the visualisation as `GeoPulse_Colourful_Category_Map.png`.
# What I learned
1. How to overlay business locations on a road network.
2. How to create geographical maps using Python.
3. How to visualise different business categories using colours.
4. How to identify geographical concentration and distribution patterns.
5. How to communicate spatial analysis results through maps.

# 24th november 2026
Work completed:
- Created a Kernel Density Estimation (KDE) heatmap using 347 business-location records.
- Analysed the geographical concentration of businesses.
- Used colour intensity to identify areas with higher and lower estimated business density.
- Generated and saved the heatmap.
Output: GeoPulse_Business_Density_Heatmap.png
