# Road Accidents in France

## Project Overview

This project explores road accident data in France between 2019 and 2023, aiming to identify the key factors influencing accident severity and to uncover demographic, temporal, and environmental trends.
It combines data cleaning, statistical testing, and interactive visualization using Python and Power BI. You will find in this github the official files as well as screenshots of the dashboard and google collab codes.

Data from: Open Data Sécurité Routière — Ministère de l’Intérieur (France)

## Objectives 

- Analyze and understand the different factors that influence road accidents 
in France (2019-2023). 

- Conduct a data audit (and use Python)  to evaluate data quality, identify 
missing values, and help us choose which columns to keep or drop. 

- Clean, standardize, and rename columns for consistency, and create new 
columns (i.e. create age column using columns year of birth and year of 
accident).  

- Using seaborn and matplotlib to create visualizations (graphs) of our 
chosen factors in terms of number of people in accidents and injury 
severity. 

- Perform statistical analyses (i.e. Chi-square tests, Cramer’s V, Logistic 
Regression) to test relationships between severity and chosen factors. 
Develop an interactive Power BI dashboard of this data for further (and 
improved) visualization. 

- Summarize findings/results and share conclusions drawn on possible 
recommendations to improve road-safety from findings.


## Tools & Statistics Used

- Python (Pandas, Seaborn, Matplotlib, SciPy)

- Power BI (interactive dashboards)

- Google Colab for code execution

- Chi-square tests, Cramer’s V, correlation analysis


## Google Colab: What each file represents

- Data _Road_Accidents_France_Audit_DA - Data audit of the CSV files downloaded from the Ministère de l’Intérieur website
- 00_road_accidents_france_data_exploration_and_file_merge.ipynb — Exploratory analysis and merging of datasets.
- 01_road_accidents_france_data_preprocessing_and_feature_engineering.ipynb — Feature engineering and variable transformation for modeling.
- 02_road_accidents_france_data_visualization.ipynb — Data visualization and exploratory statistics.
- 03_road_accidents_france_PowerBI_preprocessing.ipynb — Preparing data exports for Power BI dashboards.

## Data Cleaning & Preparation
- Merged 4 datasets (users, vehicles, places, characteristics).

- Standardized and converted types (e.g. int64, category, datetime64).

- Created grouped variables such as:

  - speed_range: (0–30, 31–50, 51–70, 71–90, 91–110, 110+)

  - age_group: (0–13, 14–17, 18–24, 25–34, …, 85+)

- Handled missing data (NaN, -1 placeholders) and removed outliers.

- (Note: For more information for each steps please read the "Project Report - Road accidents in France" that provides all the details)

## Dashboard Example

### Model View 
<img width="1802" height="1167" alt="Dashboard - Model View" src="https://github.com/user-attachments/assets/7abdfc5b-d29e-4c8b-b225-6824f0d93ee2" />

### Speed Limit Analysis Page
<img width="1921" height="1081" alt="Dashboard - Speed Limit Analysis" src="https://github.com/user-attachments/assets/98b1752e-0d11-4e8f-b27d-4c9eb1c0635c" />

### User Profile Analysis Page (with slider "Department" being used for example)
<img width="1921" height="1081" alt="image" src="https://github.com/user-attachments/assets/8af05e57-554c-4258-83e5-56ef4a5d7821" />


## Team

Project completed as part of the DataScientest Data Analyst Bootcamp (École des Mines Paris – PSL).
Team members: Oscar CANIVET, Naomi Thandi KLINGBEIL, Markus NORDMANN 
