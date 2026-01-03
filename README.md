## Project Overview
This project analyzes credit card default risk using the UCI Credit Card Default Dataset containing over 30,000 customer records. The goal is to identify customer characteristics and credit behaviors associated with higher default risk and present insights through interactive dashboards and predictive modeling.

Power BI was used for data cleaning, exploratory analysis, and interactive visualization. Python was integrated for advanced analytics, including Principal Component Analysis (PCA) and Logistic Regression, achieving approximately 77% prediction accuracy. The project provides actionable insights for banks to improve credit risk management and decision-making.

## Objectives
- Perform exploratory and diagnostic analysis of customer credit behavior  
- Identify demographic and financial factors influencing default risk  
- Build an interactive Power BI dashboard  
- Apply machine learning models to predict default likelihood  
- Translate analytical findings into business insights  

---

## Dataset Description
**Key Features:**
- Demographics: Age, Gender, Education, Marital Status  
- Credit Behavior: Credit limit, bill amounts, payment amounts, payment history  
- Target Variable: DefaultNextMonth (1 = Default, 0 = No Default)  

Source: **UCI Machine Learning Repository**

---

## Data Preparation
- Renamed unclear column names for readability  
- Removed missing and inconsistent records  
- Handled outliers  
- Created new features (total bills, total payments, age groups)  

---

## Exploratory Data Analysis (EDA)
Key findings:
- Higher default rates among younger and older age groups  
- Single customers and those with lower education default more often  
- High credit utilization strongly correlates with default risk  

---

## Power BI Dashboard
Features include:
- Interactive slicers (gender, age, education, marital status)  
- Default distribution by demographic groups  
- Credit utilization vs default likelihood  
- Key Influencers visual for risk drivers  

---

## Predictive Modeling
- **PCA** for feature importance and risk segmentation  
- **Logistic Regression (Python)** for default prediction  
- Model accuracy: **~77%**

Python libraries used:
- pandas
- scikit-learn
- matplotlib

---

## Business Insights
- High bill amounts with low payments indicate elevated risk  
- Younger, single customers need closer monitoring  
- Insights can support smarter credit approval and risk mitigation strategies  

---
