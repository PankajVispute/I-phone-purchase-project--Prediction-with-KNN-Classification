# Prediction-with-KNN-Classification
Implementation of KNN algorithm in Python 3

# Description
* K-Nearest-Neighbors algorithm is used for classification and regression problems.
* In this project, it is used for classification.
* puchased Iphone dataset used for project.

# Data set format
* CSV (Comma Separated Values) format.
* Attributes can be integer or real values.
* Responses can be integer, real or categorical.

# Overview
The primary goal is predict wheather customer will purchase Iphone or not from their store based on gender, age and salary.

# liabrary 
* pandas, numpy, matplotlib,seaborn,sklearn,joblib used in project

# Methodology
1. ## Machine learning life cycle:
   - followed indistry standard practice of machine learning life cycle steps.
2. ## Preprocessing and EDA:
   - implement necessary transformation, preprocessing of dataset.
   - conduct exploratory data analysis on dataset.
3. ## Visualization:
   - visualised data using visualisation library like matplotlib, seaborn.
4. ## Algorithm:
   - scikit library use for KNN algorithm.
5. ## model validation:
   - model validate with accuracy score of diff K, confusion metrix.
6. ## save model:
   - joblib library used to dump model.
   - model is saved in .ipynb formate as i_phone_purchase_product_using_KNN_model.
# EDA:
- Total female are 51% and male are 49%.
- Female average salary is more than male average salary.
- Total iphone purchased - 143 no's ( female purchased - 77 no's and male purchased - 66 no's)
- Maximum iphone purchased between age group of 46 to 50 years.( female - 47 to 48 yrs, male - 46 to 50 yrs)
- No correlation between salary with age and salary with number of iphone purchased.

# KNN model:
- model validated with k values 19, 21 and 15 which was calculated by standard method and error method.
- accurancy score of k=15 is 0.875, so it is greater than other model.So it is considered and saved.
  
