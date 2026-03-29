# Netosole_Bootcamp_Tasks (Overall)
This repository contains all tasks and assignments completed during the AI/ML Bootcamp at NetSol. It includes exercises on data analysis, machine learning, and problem-solving
Data Cleaning Project
This project is part of my NAVTTC Data Science Bootcamp at NetSol.

# File 1 Data_Clearning_Lab (Description)
This notebook demonstrates basic data cleaning techniques such as:

Handling missing values
Removing duplicates
Data formatting
Note
This project is based on instructor-provided material. I have executed and reviewed the notebook.


## File 2: Data Wrangling&Filetring.ipynb
**Description:**  
This notebook performs initial data cleaning and transformation, including:  
- Handling missing values  
- Renaming columns  
- Converting data types  
- Creating new derived columns for analysis
*Apply filtering steps in notebook

**Input:** Raw dataset (CSV file)  
**Output:** Cleaned and transformed dataset ready for filtering and analysis  
Filtering rows based on conditions (e.g., dates, values, categories)
Removing duplicates
Selecting specific columns for modeling or visualization

## File 3: Exploratory Data Analysis (EDA).ipynb
**Description:**  
This notebook performs a comprehensive exploratory data analysis to understand patterns, distributions, and relationships in the dataset. Key tasks include:  
- Summary statistics for numerical and categorical columns  
- Visualizations: histograms, boxplots, scatter plots, and correlation heatmaps  
- Identifying outliers and anomalies  
- Insights generation for further analysis or modeling  

**Input:** Filtered dataset from Data Filtering.ipynb  
**Output:** Visualizations and insights report highlighting key patterns in the data  

**Usage Example:**
```python
# Load filtered data and run EDA
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt

filtered_data = pd.read_csv('filtered_data.csv')
# Perform EDA steps from notebook

Author
Muhammad Arfan Wazeer
