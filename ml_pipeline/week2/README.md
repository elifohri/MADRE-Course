# 📘 ML Pipeline – Week 2: Modeling & Evaluation (Logistic Regression)

This notebook is the second step in our pipeline, focusing on scaling, dimensionality reduction (PCA), and model training/evaluation for binary intrusion detection. It builds on Week 1’s prepared dataset and sets the stage for later weeks on model tuning and deployment.

## Link to Notebook
https://colab.research.google.com/drive/1-ByOAYGg6TTLQwJiDLj-EJMIAu_0EkQn?usp=sharing

## How to Run
The workflow is optimized for Google Colab:
- Click **“Open in Colab”** at the top of the notebook
- Run cells in order

## Learning Objectives
- Understand why scaling matters for linear models  
- Apply PCA to reduce noise and redundancy  
- Build a leakage-safe Pipeline (Scaling → PCA → Logistic Regression)  
- Use cross-validation properly on the training set  
- Evaluate the model

## Contents
1. Problem Overview  
   - Binary classification: **Benign (0)** vs **Attack (1)**  
2. Data Split  
   - train/test split  
3. Preprocessing  
   - Standardization
   - PCA
4. Modeling  
   - Logistic Regression with regularization  
   - Pipeline + cross-validation
5. Evaluation  
   - Accuracy & Classification Report
   - Confusion Matrix (heatmap)  
   - ROC Curve & AUC
   - Precision–Recall Curve
6. Discussion  
   - Impact of scaling & PCA on results  
   - Error analysis (FP/FN)

## Dependencies
Install the following in Colab:
```bash
pip install numpy pandas scikit-learn matplotlib seaborn pyarrow gdown

