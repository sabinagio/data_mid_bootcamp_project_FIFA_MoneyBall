# Ironhack - Mini-Project

## Business Background

**Position:** Data Analyst  
**Business:** Romanian Soccer Team    
**Business Objective:** Understanding what drives the overall score of a FIFA 19 player and deriving scores for new players in the game for future selections.  

## Data Science Process

### [1. Data Review & Cleaning (Pandas)](https://github.com/sabinagio/data_mid_bootcamp_project_FIFA_MoneyBall/blob/master/notebooks/mini-project%20-%201.%20Data%20Review%20%26%20Cleaning.ipynb)
The data review & cleaning process involved:
- understanding the meaning and relevance of player features using information available online
* development of functions that would format the data for further use in prediction models

### [2. Exploratory Data Analysis (Matplotlib, Seaborn)](https://github.com/sabinagio/data_mid_bootcamp_project_FIFA_MoneyBall/blob/master/notebooks/mini-project%20-%202.%20EDA.ipynb)
During the exploratory data analysis process, columns that were either highly correlated with each other or not providing value to the regression model were eliminated.

### [3. Regression Model Evaluation (Scikit-Learn)](https://github.com/sabinagio/data_mid_bootcamp_project_FIFA_MoneyBall/blob/master/notebooks/mini-project%20-%203.%20Modelling%20%26%20Evaluation.ipynb)
The linear regression model performed perfectly when used on the testing data, suggesting that the overall score was calculated from the other features to begin with.
