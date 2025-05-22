# Airbnb Superhost Prediction Project

This repository contains our team project for the AIBD course at Purdue University, focused on predicting Airbnb Superhost status using machine learning techniques.

## 📌 Objective
To develop a predictive model that identifies:
- Hosts who are likely to become Airbnb Superhosts.
- Current Superhosts at risk of losing their status.

## 📊 Dataset
We used Airbnb data from **Chicago**, which has one of the highest concentrations of Superhosts. The dataset includes:
- Host activity (reviews, response times, cancellations)
- Booking behavior
- Revenue and occupancy patterns

## 🧠 Methods Used
- **Data Cleaning & Preprocessing**  
  - Missing value imputation  
  - Outlier handling  
  - Multicollinearity reduction using VIF  

- **Feature Engineering**  
  - Correlation analysis  
  - Chi-square test for categorical features  

- **Modeling Techniques**  
  - Random Forest (best-performing model)  
  - XGBoost  
  - LightGBM  
  - Stratified K-Fold Cross-Validation  

## 🔍 Key Results
- **Random Forest Accuracy:** 97.26%  
- **ROC-AUC:** 99.52%  
- Superhost status is strongly correlated with:
  - Review count and quality
  - Occupancy rate
  - Response time and cancellation rates

## 📂 Files Included
- `Predicting-Superhost-Status-A-Data-Driven-Approach-gamma (1).pptx`  
  Final project presentation summarizing the analysis, insights, and recommendations.

- `AIBD_Team_Project edited.ipynb`  
  Complete Jupyter Notebook with EDA, preprocessing, model building, and evaluation.

## 📈 Business Impact
- Helps Airbnb identify and support top-performing hosts.
- Provides insights to improve platform engagement and revenue.
- Recommends targeted interventions for at-risk Superhosts.

## 👥 Team
- Krithiga Rajan Sangeetha Rajan  
- Nandini Devalla  
- Shashank Sridhar

---
