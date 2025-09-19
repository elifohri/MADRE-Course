# 📘 ML Pipeline – Week 1: Data Preparation  

This notebook is the first step in building a machine learning pipeline, focusing on **data preparation**. The goal is to understand raw datasets, clean them and prepare them for modeling. This forms the foundation of the ML pipeline, preparing us for Week 2: **Exploratory Data Analysis (EDA)** and further modeling.    

## Learning Objectives  
- Learn how to import and combine multiple datasets.  
- Understand dataset structure (rows, columns, types).  
- Detect and visualize missing data.  
- Apply basic preprocessing (encoding, cleanup).

## How to Run  
The dataset used here is large, so the most efficient way to work with it is on **Google Colab**.  

- Click the **“Open in Colab”** button at the top of the notebook.  
- Sign in with your personal Google account.  
- Start a Colab session and run the cells step by step.

## Contents  

1. Problem Understanding
   - Define the problem
   - Identify goals and success criteria 

2. Data Collection
   - Download datasets from Google Drive.  
   - Unzip and load into `pandas` DataFrames.  
   - Combine multiple datasets into a single working dataset.  

3. Data Preparation
   - Detect and remove duplicate records.  
   - Identify and handle infinite values.  
   - Explore missing data and handle appropriately.  
   - Select relevant features
   - Encode categorical variables
   - Identify imbalanced target classes
   - Train-test split for building ML models

4. Data Visualization: 
   - Visualize distributions of numerical and categorical features.  

## Dependencies  
This notebook requires the following Python libraries:  

```bash
pip install numpy pandas seaborn missingno scikit-learn gdown matplotlib
```  
