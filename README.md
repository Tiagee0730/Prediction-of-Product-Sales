# Prediction-of-Product-Sales
- Tia Gee
### Introduction
Our goal is to product helpful analysis of sales for each item sold by a group of stores
## The Data:
- The source of the data used in this project was from Kaggle.
  -[Kaggle Link] (https://www.kaggle.com/datasets/shivan118/big-mart-sales-prediction-datasets?select=train.csv)
### To prepare this data, this data was cleaned and the following processes were performed:

## Exploratory Data Analysis
- During the exploratory data analysis, a boxplot and histogram was visualized for numeric datatype columns. 
- Also, a barplot was visualized for a categorical column. 
- This gave a good baseline for all of the numeric and categorical columns for univariate EDA.

  #### Visual 1
<img width="815" alt="Screenshot 2023-05-08 at 7 57 45 PM" src="https://user-images.githubusercontent.com/129705333/236967991-c9d35bd6-32ad-4fff-b860-7de3e4a20ea1.png">
### Revelence : Based on the data, Tier 3 supermarkets make the most money and is the market I suggest you model future stores as to drive the highest projected sales.
  
  
  ## Machine Learning Using the Following Models
  - Linear Regressor Model
  - Decision Tree Regressor Model

## Models Evaluated and Results
- Linear Regression Model (Testing Set)
  -   R2 :  0.5678354334123267
  -   RMSE : 1092.8771481811818
- Decision Tree Regressor Model (Testing Set)
  -   R2 : 0.3667631826343053
  -   RMSE : 1498.3010906396064

## The final model choosen
- Linear Regression model

## Recommendations
- I recommend that the stores build Tier 2 supermarkets because they perform best in this market. The linear regression model predicts well for store sales.

## For further information, please contact at 
ashley.gee0730@gmail.com
