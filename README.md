# Ironhack - Mini-Project

## Business Background

**Position:** Data Analyst  
**Business:** Romanian Soccer Team    
**Business Objective:** Understanding what drives the overall score of a FIFA 19 player and deriving scores for new players in the game for future selections.  

## Data Science Background

**Data**: The data set consists of information on 18,000 current bank customers in the study. 

**Data Science Objectives:** 
- Find the type of clients accepting credit card offers
- Build a classification model able to predict if future customers are likely to accept a credit card offer based on their characteristics (to allow targetted customer offers)
- Offer recommendations to the bank based on findings, e.g. if it should focus more on a specific type of loyalty program or client type
- Provide ideas for further exploration & analysis, e.g. which credit card customer segment is the most profitable

## Data Science Process

### [1. Data Review & Cleaning (Pandas)]()
The data review & cleaning process involved:
- understanding the meaning and relevance of player features using information available online
* development of functions that would format the data for further use in prediction models

### [2. Exploratory Data Analysis (Matplotlib, Seaborn)]()
During the exploratory data analysis process, columns that were either highly correlated with each other or not providing value to the regression model were eliminated.

### [3. Regression Model Evaluation (Scikit-Learn)]()
The linear regression model performed perfectly when used on the testing data, suggesting that the overall score was calculated from the other features to begin with.
