# france-road-accidents

Project Overview

This project explores road accident data in France between 2019 and 2023, aiming to identify the key factors influencing accident severity and to uncover demographic, temporal, and environmental trends.
It combines data cleaning, statistical testing, and interactive visualization using Python and Power BI.

Objectives

Analyze and understand the different factors that influence road accidents 
in France (2019-2023). 

Conduct a data audit (and use Python)  to evaluate data quality, identify 
missing values, and help us choose which columns to keep or drop. 

Clean, standardize, and rename columns for consistency, and create new 
columns (i.e. create age column using columns year of birth and year of 
accident).  

Using seaborn and matplotlib to create visualizations (graphs) of our 
chosen factors in terms of number of people in accidents and injury 
severity. 

Perform statistical analyses (i.e. Chi-square tests, Cramer’s V, Logistic 
Regression) to test relationships between severity and chosen factors. 
Develop an interactive Power BI dashboard of this data for further (and 
improved) visualization. 

Summarize findings/results and share conclusions drawn on possible 
recommendations to improve road-safety from findings.


Tools & Technologies

Python (Pandas, Seaborn, Matplotlib, SciPy)

Power BI (interactive dashboards)

Google Colab for code execution

Chi-square tests, Cramer’s V, correlation analysis

Data from: Open Data Sécurité Routière — Ministère de l’Intérieur (France)


Data Cleaning & Preparation

Merged 4 datasets (users, vehicles, places, characteristics).

Standardized and converted types (int64, category, datetime64).

Created grouped variables such as:

speed_range: (0–30, 31–50, 51–70, 71–90, 91–110, 110+)

age_group: (0–13, 14–17, 18–24, 25–34, …, 85+)

Handled missing data (NaN, -1 placeholders) and removed outliers.



Team

Project completed as part of the DataScientest Data Analyst Bootcamp (École des Mines Paris – PSL).
Team members: Oscar CANIVET, Naomi Thandi KLINGBEIL, Markus NORDMANN 
