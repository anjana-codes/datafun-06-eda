# datafun-06-eda

Title: Specification for Project 6 EDA Notebook
	
 Anjana Dhakal, 
 May 30,2024
 updated: June, 5,2024	

## Overview
Project 6 is an opportunity to create my own custom exploratory data analysis (EDA) project using GitHub, Git, Jupyter, pandas, Seaborn, and other popular data analytics tools.

## Objectives
Perform and publish a custom EDA project to demonstrate skills with Jupyter, pandas, Seaborn, and popular tools for data analytics. The notebook should tell a data story and visually present findings in a clear and engaging manner.

## Create GitHub Repository
```
 GitHub Repository: datafun-06-eda
 Documentation: README.md
 Notebook: anjana_eda.ipynb
 
```

## Clone to VS Code 
```
git clone site_URL
```

## Adding files 
- Add a .py file to work in.
- Add a requirements.txt file to hold the required project modules.
- Create a .venv to act as the virtual environment.
- Include a .gitignore file to exclude the .venv file from the rest of the Python environment.
  
## Create Project Virtual Environment
```
 py -m venv .venv
.venv\Scripts\Activate
```
## Install all Required Packages
```
py -m pip install jupyterlab
py -m pip install numpy
py -m pip install pandas
py -m pip install matplotlib
py -m pip install seaborn
 py -m pip freeze > requirements.txt
```

## Git add and commit
```
git add .
git commit -m "start a project"
git push origin main
```

##  Import Dependencies
```
#importing dependencies
import matplotlib.pyplot as plt
import pandas as pd
import seaborn as sns
import numpy as np

```
## Data source: car_crashes.csv

This 'car_crashes.csv' dataset from the Seaborn library contains data about car crashes in the United States. It contains eight columns and here is an explanation of the columns in this dataset:
1. total: total number of car crashes per 100 million miles driven
2. speeding: proportion of drivers involved in fatal crashes who were speeding (as a percentage)
3. alcohol: proportion of drivers involved in fatal crashes who were alcohol-impaired (as a percentage)
4. not_distracted: proportion of drivers involved in fatal crashes who were not distracted (as a percentage).
5. no_previous: proportion of drivers involved in fatal crashes with no previous incidents  (as a percentage).
6. ins_premium: average insurance premium in the state
7. ins_losses: average insurance losses in the sate per insured driver
8. abbrev: abbreviation of the U.S. state name

Dataset link: https://github.com/mwaskom/seaborn-data/blob/master/car_crashes.csv

## Exploratory Data Analysis
1. Data Acquisition
2. Initial Data Inspection
3. Initial Descriptive Statistics
4. Initial Data Distribution for Numerical Columns
5. Initial Data Distribution for Categorical Columns
6. Initial Data Transformation and Feature Engineering
7. Initial Visualizations

## Repeat git add and commit
```
git add .
git commit -m "project is done"
git push origin main
```

## Source
This project was built to the following specifications: https://github.com/denisecase/datafun-06-spec


