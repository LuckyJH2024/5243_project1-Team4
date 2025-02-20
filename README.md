# README: Exploratory Data Analysis for Communities and Crime Dataset
## Overview
This project performs Exploratory Data Analysis (EDA) on a subset of the Communities and Crime dataset, focusing on socioeconomic and housing features that may influence violent crime rates. The analysis includes data visualization, correlation analysis, scatter plots, bar charts, and feature engineering.
## Prerequisites
Before running the code, ensure that you have the following dependencies installed:
### Required Libraries
`pip install pandas matplotlib seaborn numpy statsmodels sklearn itertools scipy tqdm math`
## Running the Code
### 1. Jupyter Notebook (Recommended)
If using Jupyter Notebook, open and run `Full_code_V1.ipynb` step by step.

`jupyter notebook Full_code_V1.ipynb`
### 2. Python Script Execution
If converted to a Python script (`.py` file), run the script as follows:

`python Full_code_V1.py`
### Data
- You do not need the raw dataset `raw_data.csv` downloaded to run the code, it is fetched directly via a url.
- An intermediate dataset `cleaned_selected_features.csv` will be created after the data cleaning & inconsistency handling. It should be in the same directory as the code file.
- The final dataset `cleaned_selected_features_engineered.csv` is produced after the feature engineering.
### Note
If running in an IDE, execute the code cell by cell for better visualization.

