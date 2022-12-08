## Classification - Churn For Bank Customer

**Problem Statement**
![4](https://user-images.githubusercontent.com/108534539/206376148-34a51aee-2994-442f-ba5b-d729eb7f0244.jpg)

The purpose of this project is to analyze the bank customer behavior patterns and to decrease churn rate. The results show that page values, the number of visited pages, has the greatest impact on a visitor's purchase decision. The conversion rate to purchase increases up to 60% by applying an actionable recommendation from insights that boost the number of visited pages.

![5](https://user-images.githubusercontent.com/108534539/206376218-cf68a962-07a8-49d1-80bb-f9c30d2aff94.jpg)

**Tools**: Python, JupyterLab, Git

**Libraries**: Pandas, Numpy, Feature-engine, Scikit-learn, Imbalanced-learn, SHAP-learn, Gain & Lift Analysis

**Dataset**: Predicting Churn for Bank Customers [[source]](https://www.kaggle.com/datasets/adammaus/predicting-churn-for-bank-customers)

**Summary of the analysis**
* This dataset has 10000 observations and 14 variables with 11 numerical variables, 3 categorical variables and one target variable.
* All numerical variables have a right-skewed distribution and contain a lot of outliers. 
* Exited is the target variable that labels a 0 (not churn) and 1 (churn). The current condition is 20% of customer churn 
* From exploratory data analysis, customer who use num of products > 2 have trend churn, The older the customer, the higher the churn rate
* Based on data characteristics, the selected algorithm to build a classification model is tree-based or ensemble. The classification model with the xgboost algorithm is able to correctly predict 75% of visitors who make a purchase.
* Age, NumOfProduct, Gender Male, Geography France and IsActiveMember are the biggest impact on churn rate.
* Percentage Saving cost with model have 69%

![17](https://user-images.githubusercontent.com/108534539/206376346-866c1ee0-85a7-461b-a8ad-c68f483a7498.jpg)

![18](https://user-images.githubusercontent.com/108534539/206376392-b9f6fedb-44b5-4f3c-bf3c-7f40f0162376.jpg)


**What I have learned**
* Framing the business problem. 
* Create a machine learning model and extract insight from it to make an actionable recommendation for the business team.
* Make a business simulation from insights that decrease churn rate.

**File Dictionaries**
* [EDA_2Pendo (1).ipynb](https://github.com/archie-cm/churn-for-bank-customer/blob/main/EDA_2Pendo%20(1).ipynb): this notebook contains all of project details, such as business understanding, exploratory data analysis & insights from dataset and external data.
* [Supervised_2pendo.ipynb](https://github.com/archie-cm/churn-for-bank-customer/blob/main/Supervised_2pendo.ipynb) : data preprocessing, modeling, lift & gain analysis, feature importance with SHAP, business recommendation
* [2pendo-presentation_final_project.pdf](https://github.com/archie-cm/churn-for-bank-customer/blob/main/2pendo-presentation_final_project.pdf): summary of the project.
