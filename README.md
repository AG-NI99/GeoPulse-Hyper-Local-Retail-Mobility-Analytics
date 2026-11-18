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
