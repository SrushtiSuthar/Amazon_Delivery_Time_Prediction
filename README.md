# Amazon Delivery Time Prediction 

## Overview  
This project aims to **predict delivery time** for Amazon orders based on features like agent info, order metadata, geography (store & drop locations), weather, traffic, and more.  
It includes exploratory data analysis (EDA), data wrangling/preprocessing, and a full machine-learning pipeline — giving a realistic, end-to-end data science project that’s easy to understand and reproduce.

---

## Repository Structure
Amazon_Delivery_Time_Prediction/
│
├── README.md
├── Dataset/ ← Folder containing all data files
│ ├── raw/ ← Raw data CSV
│ ├── wrangled/ ← Cleaned / wrangled dataset
│ └── processed/ ← Final preprocessed dataset used for modeling
│
├── Amazon_Delivery_Time_Prediction_EDA.ipynb ← Notebook for Exploratory Data Analysis & Hypothesis
└── Amazon_Delivery_Time_Prediction.ipynb ← Notebook for Data Preprocessing, Model Training & Evaluation

## What’s Inside

### Exploratory Data Analysis (EDA)  
- Data overview (shape, statistics, missing values)  
- Distribution of target variable (delivery time)  
- Analysis of categorical features (e.g. weather, traffic, vehicle, area, category)  
- Analysis of numerical features (agent age, rating, etc.)  
- Geographic visualization (store vs drop locations)  
- Initial hypotheses about factors influencing delivery time  

### Data Wrangling & Preprocessing + Modeling  
- Handling missing values  
- Geolocation feature engineering (distance between store and drop)  
- Optional derived features (time of order, order pickup time difference, etc.)  
- Encoding categorical variables & scaling numerical variables  
- Outlier treatment (e.g. winsorizing delivery time)  
- Train/test split, model training (e.g. Random Forest or other regressors)  
- Model evaluation (MAE, MSE, RMSE, R²)  
- Saving processed dataset for reproducibility and reuse  

---

## Requirements  

To run the notebooks, you need the following Python libraries:
pandas
numpy
scikit-learn
matplotlib
seaborn
joblib

---

##  How to Run

1. Clone or download the repository.  
2. Place raw data CSV under `Dataset/raw/`.  
3. Open and run `Amazon_Delivery_Time_Prediction_EDA.ipynb` to explore data & hypotheses.  
4. Open and run `Amazon_Delivery_Time_Prediction.ipynb` for preprocessing, modeling, and evaluation.  
5. (Optional) Save or export results, processed data, or final model for future use.  

---

## Purpose & Why This Project Matters

- Demonstrates end-to-end data science workflow: from raw data → EDA → preprocessing → modeling → evaluation  
- Highlights ability to handle real-world data issues (missing values, geolocation, feature engineering, outliers)  

---

## Author  

**Srushti Suthar** — Data Science & Machine Learning Enthusiast / Intern
