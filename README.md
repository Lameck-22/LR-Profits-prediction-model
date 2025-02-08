# Linear Regression model predicting the profits of given companies
This project aims to predict the profits of company(s) given certain parameters, Linear regression model was used trying to achieve this.
Before diving into the model creation, data cleaning,preprocessing and EDA performance was essential.
First I installed scikit-learn using
`%pip install scikit-learn`
- From sklearn I imported various packages like: 
  1. linear_model
  2. metrics
  3. model_selection

- linear_model was used to perform linear regression and find the best fit line
- model_selection was used to train_test_split the data
- metrics was used to test the accuracy of the model, in this case we used r2_score which rates the model between 0-1; when the value is higher then the model is good

- The dependent variable was profits while the dependent variables were; R&D Spend, Administration, Marketing Spend
- This was a multi-linear regression model
