# Datasets-Analysis

# Analysis and Machine Learning on Multiple Datasets

## 📌 Project Overview
This project involves data analysis and machine learning applied to **five different datasets**. The goal is to extract insights, preprocess data, and build predictive models.

## 📂 Datasets
The analysis is performed on the following datasets:
1. **smart_grid** 
2. **RedWineQuality** 
3. **coffee_shop_revenue** 
4. **AI_resume** 
5. **Dataset 5** 

## 🔬 Machine Learning Models
The following machine learning techniques have been applied:
- Linear Regression, Decision Trees
- Model evaluation metrics like accuracy, precision, recall, and F1-score were used.

## 🛠️ Installation & Dependencies
To run this project, install the required dependencies using:
```bash
pip install -r requirements.txt
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
!pip install ydata-profiling
from ydata_profiling import ProfileReport
profile = ProfileReport(df ,explorative = True )
profile.to_notebook_iframe()  # For Jupyter Notebooks
profile.to_file("your_report.html")
from sklearn.linear_model import LogisticRegression
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import StandardScaler
from sklearn.metrics import accuracy_score, classification_report, confusion_matrix
