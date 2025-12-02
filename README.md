# Road Accidents in France

## Project Overview

This project explores road accident data in France between 2019 and 2023 (this represents 270,000 road accidents in France or 600,000 people involved) aiming to identify the key factors influencing accident severity and to uncover demographic, temporal, and environmental trends.
It combines data cleaning, statistical testing, and interactive visualization using Python and Power BI. You will find in this github the official files as well as screenshots of the dashboard and google collab codes.

Data from: Open Data Sécurité Routière — Ministère de l’Intérieur (France) --->
https://tinyurl.com/39cu4527

## Objectives of the Project

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

## Key Findings & Results
- Temporal patterns show that **severe injuries** are most likely during the **early morning hours** and on **weekends**.
  
- The strongest severity risk group is **85 and older**, with more than three times the odds of severe accidents compared to children.
  
- Accident density is highest in **urban centers**, but the **probability of severe injury** is greatest in **rural regions**.
  
- Severity increases with speed limits: **high-speed roads** produce the **highest share of severe and fatal cases**.
  
- Bikes and e-bike riders have **27% severe injuries**, compared to around **18% for other vehicles**.

Overall, our findings revealed that **injury severity is NOT random** but associated with identifiable patterns and **NOT influenced by one factor alone** but **multiple factors combined** together.
## Tools & Statistics Used

- Python (Pandas, Seaborn, Matplotlib) and Google Colab for code execution.

- Power BI (interactive dashboards).

- Chi-square tests, Cramer’s V, correlation analysis.

## What Each Folder Contains

### Project Report folder
- *Project Report - Road accidents in France.pdf*

  └──> A full report detailing every step of our project (e.g, data cleaning, dashboard design, statistical analysis).
### Google Colab folder
- *Data _Road_Accidents_France_Audit_DA* 

  └──> Data audit of the CSV files downloaded from the Ministère de l’Intérieur website.
- *00_road_accidents_france_data_exploration_and_file_merge.ipynb*
  
  └──> Exploratory analysis and merging of datasets.
- *01_road_accidents_france_data_preprocessing_and_feature_engineering.ipynb* 

  └──> Feature engineering and variable transformation for modeling.
- *02_road_accidents_france_data_visualization.ipynb* 

  └──> Data visualization and exploratory statistics.
- *03_road_accidents_france_PowerBI_preprocessing.ipynb* 

  └──> Preparing data exports for Power BI dashboards.

### Dashboard folder 
- *04_road_accidents_france_PowerBI_dashboard.pbix*

  └──> The handed-in dashboard for the capstone project.
- *04_road_accidents_france_PowerBI_dashboard_PRESENTATION.pbix*

  └──> The dashboard used for our presentation, the organization and interactions being the main differences.

### Screenshot folder
- Each page created in our PowerBI dashboard (order from start to end):

  └──> 1. *Dashboard - Executive Summary.png*
  
  └──> 2. *Dashboard - Temporal Analysis.png*
  
  └──> 3. *Dashboard - User Profile Analysis.png*
  
  └──> 4. *Dashboard - Location Analysis.png*
  
  └──> 5. *Dashboard - Speed Limit Analysis.png*
  
  └──> 6. *Dashboard - Bike and Severity.png*
  
  └──> 7. *Dashboard - Conclusion.png*

- Model view highlighting the relationships between all tables:

  └──> 1. *Dashboard - Model View.png*

### Examples
#### Example 1: *00_road_accidents_france_data_exploration_and_file_merge.ipynb Sample*
<img width="1023" height="698" alt="image" src="https://github.com/user-attachments/assets/0394b5d5-c625-4727-8577-dd3a9c1b992c" />

#### Example 2: *Dashboard - Model View* 
<img width="1802" height="1167" alt="Dashboard - Model View" src="https://github.com/user-attachments/assets/7abdfc5b-d29e-4c8b-b225-6824f0d93ee2" />

#### Example 3: *Dashboard - Speed Limit Analysis* 
<img width="1921" height="1080" alt="Dashboard - Speed Limit Analysis" src="https://github.com/user-attachments/assets/98b1752e-0d11-4e8f-b27d-4c9eb1c0635c" />

## Team

Project completed as part of the DataScientest Data Analyst Bootcamp (École des Mines Paris – PSL).


Team members: 

- Oscar CANIVET, 

- Naomi Thandi KLINGBEIL, 

- Markus NORDMANN 
