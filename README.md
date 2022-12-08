## Classification - Churn For Bank Customer

![4](https://user-images.githubusercontent.com/108534539/206376148-34a51aee-2994-442f-ba5b-d729eb7f0244.jpg)

The purpose of this project is to analyze the purchasing behavior patterns of e-commerce visitors and to increase the conversion rate to purchase. The results show that page values, the number of visited pages, has the greatest impact on a visitor's purchase decision. The conversion rate to purchase increases up to 60% by applying an actionable recommendation from insights that boost the number of visited pages.

![5](https://user-images.githubusercontent.com/108534539/206376218-cf68a962-07a8-49d1-80bb-f9c30d2aff94.jpg)

**Tools**: Python, JupyterLab, Git

**Libraries**: Pandas, Numpy, Feature-engine, Scikit-learn, Imbalanced-learn

**Dataset**: Online Shoppers Purchasing Intention, UCI Machine Learning, 2018 [[source]](https://www.kaggle.com/datasets/imakash3011/online-shoppers-purchasing-intention-dataset)

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
* Make a business simulation from insights that calculate the increase in the conversion rate.

**File Dictionaries**
* [EDA_2Pendo (1).ipynb](https://github.com/archie-cm/churn-for-bank-customer/blob/main/EDA_2Pendo%20(1).ipynb): this notebook contains all of project details, such as business understanding, exploratory data analysis & insights, data preprocessing and modeling.
* [presentation-appendix.ipynb](https://github.com/irfan-fadhlurrahman/online-shoppers-purchasing-intention/blob/main/presentation-appendix.ipynb): this notebook contains all data visualizations for presentation slides and the details of business simulation, a calculation of increased conversion rate after applying an actionable recommendation.
* [Final Project Presentation Slides.pdf](https://github.com/irfan-fadhlurrahman/online-shoppers-purchasing-intention/blob/main/Final%20Project%20Presentation%20Slides.pdf): summary of the project.
