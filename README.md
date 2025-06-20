# 📊 Employee Attrition Prediction  

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)  
[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.0+-orange)](https://scikit-learn.org/)  
[![Pandas](https://img.shields.io/badge/Pandas-1.3+-brightgreen)](https://pandas.pydata.org/)  

**Predicting employee turnover using data analysis and machine learning to help organizations reduce attrition.**  

---

## 🔍 Overview  
This project analyzes employee attrition by leveraging **Exploratory Data Analysis (EDA)** and **machine learning models**. The goal is to identify key factors driving employee turnover and build a predictive model to help HR teams take proactive retention measures.  

---

## 🚀 Key Features  
✔ **Exploratory Data Analysis (EDA)**  
- Visualized trends and correlations  
- Identified class imbalance in `Attrition`  
- Analyzed feature distributions
- ![]

✔ **Data Preprocessing**  
- Encoded categorical variables (`BusinessTravel`, `Department`)  
- Handled missing values  
- Feature selection  

✔ **Machine Learning Models**  
| Model            | Accuracy 
|------------------|----------
| Random Forest    | 87%      


✔ **Model Evaluation**  
- Generated classification reports  
- Confusion matrix analysis  

---

## 📂 Dataset  
**`HR-Employee-Attrition.csv`** (1,470 employees × 35 features)  
```python
import pandas as pd
df = pd.read_csv("HR-Employee-Attrition.csv")
print(df.shape)  # (1470, 35)
