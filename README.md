# uk-crime-southern-england

UK Crime Data Analysis - Python Project

This README file guides through:

-Library Usage
-File Navigation
-Project Structure

Project Overview

This project analyses UK police crime data to provide insights that support real estate decision-making. The analysis was conducted for a stakeholder, Nadine Green (Head of Sales), who requested an overview of crime trends across multiple police force areas to identify locations that may be more or less desirable for property sales.

The project uses publicly available police crime data covering the period January 2024 to December 2025 across four police force regions:

- Thames Valley Police
- Hampshire Constabulary
- Sussex Police
- Surrey Police

The analysis includes data preprocessing and exploratory data analysis (EDA) which involves spatial crime mapping. The final outcome is the recommendation of two police forces for further investigation in a later stage of analysis.

Library Usage

Several Python libraries were used to support data loading, preprocessing, analysis, and visualisation-making throughout the project.

glob - used to locate and load multiple CSV files from the dataset folders, allowing all monthly crime and outcome files to be loaded automatically without manually specifying each file.

os - used for basic file and directory management when accessing files within the project

pandas - main library used for data preprocessing, to load datasets, merge crime and outcome data, perform data quality checks, handle missing values, and create aggregated tables for analysis.

matplotlib - used to create the charts used in the EDA

seaborn - used to improve visual styling of shirts and provide clearer statistical visualisations 

matplotlib.dates - used to format the monthly time-series charts

geopandas - used to convert latitude and longitude coordinates into spatial data and create maps showing the geographic distribution of crimes

contextily - used to add baseman layers to the maps, providing geographic context

File Navigation

To understand the project from start to finish, it is recommended to review the files in the following order:

1. Project Statement of Work (Submissions folder) – understand project objectives
2. README (GitHub Repository and Submissions folder) – overview of the project structure
3. Trello Scrum Board – view project task management
4. Raw Dataset (Submissions folder) – original data source
5. Data Preprocessing Notebook 'data_preprocessing,ipynb' (GitHub Repository and Submissions folder) – data preparation process
6. Preprocessing Flowchart (Submissions folder) – visual overview of preprocessing logic
7. Processed Dataset (Submissions folder) – cleaned dataset used for analysis
8. EDA Notebook 'eda.ipynb' (GitHub Repository and Submissions folder) – exploratory analysis and visualisations
9. EDA Report (Submissions folder) – final insights and recommendations

Project Structure

The project consists of several files and resources that document the workflow from planning to analysis. Below is a guide to each file and how they relate to one another:

1. Project Statement of Work

File name: TalineManuelian_Python_PythonforDataAnalysis_Crime_ProjectStatementofWork.pdf

This document defines the project objectives, scope, deliverables, and stakeholder requirements. It outlines the purpose of the analysis and describes the expected outputs. This provides the initial definition and context for the project. 

2. Scrum Board (Trello)

Link: https://trello.com/invite/b/6980b1117eaef5c7a0b01007/ATTI6c59f1b60024857a0472ace9279fa9534CF95F62/python-crime-project-tasks-scrum-board

The Trello Board was used to manage project tasks using an agile workflow. It contains lists representing stages of progress during the project. Each card represents a task such as data preprocessing, data quality checks, exploratory data analysis, and report writing. This board demonstrates project management and task tracking throughout the analysis process. 

3. GitHub Repository

Link: https://github.com/tal333/uk-crime-southern-england

The GitHub repository contains:

data_preprocessing.ipynb - Data preparation notebook
eda.ipynb Exploratory Data Analysis notebook
README.md - Project documentation and navigation guide

4. Raw Dataset

File name: crime_data.zip

This folder contains the original dataset downloaded from the UK Police data portal. 
The dataset includes monthly CSV files containing street crime records, crime outcomes, geographic coordinates, LSOA identifiers, and police force jurisdiction. These files represent the unprocessed source data used in the project. This must be downloaded from the SharePoint submissions folder and kept in 'Downloads'. It must then be unzipped.

5. Processed Dataset

File name: Crimes_with_Outcomes_2024_2025.csv.zip

This file contains the cleaned and merged dataset created during the preprocessing stage. This dataset is used as the input for the EDA notebook. This must be downloaded from the SharePoint submissions folder and kept in 'Downloads'. It must then be unzipped.

6. Data Preprocessing Notebook

File name: data_preprocessing.ipynb

This notebook prepares the raw dataset for analysis. The output of this notebook is the processed dataset used in the EDA stage. 

7. Data Preprocessing Flowchart

File name: TalineManuelian_Python_PythonForDataAnalysis_CrimeProject_PreprocessingFlowchart.png

This diagram visually illustrates the logical workflow used during the preprocessing stage as a sequence of all the steps done in the Jupyter Notebook.

8. Exploratory Data Analysis Notebook 

File name: eda.ipynb

This notebook performs the main exploratory data analysis, creating visualisations such as charts and spatial crime maps to be used in the final report to support recommendations.

9. Exploratory Data Analysis Report

File name: TalineManuelian_Python_PythonForDataAnalysis_CrimeProject_EDAReport.pdf

The report summarises the insights discovered during the analysis that are of interest to the stakeholder at hand. It includes an executive summary along with the final recommended police forces for further investigation. 


Author

Created by Taline Manuelian

Project developed as part of a Python for Data Analysis assignment.
