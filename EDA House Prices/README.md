Building Machine Learning Pipelines: Data Analysis Phase

In this project, I have created Machine Learning Pipelines considering all the life cycle of a Data Science Projects.

Project Name: House Prices: Advanced Regression Techniques

The main aim of this project is to predict the house price based on various features.

Dataset :
https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data

Lifecycle In A Data Science Projects
1. Data Analysis
2. Feature Engineering
3. Feature Selection
4. Model Building
5. Model Deployment

1.Data Analysis
  1.a) Missing Values: How many features have missing values?

  1.b) Numerical Variables : How many features are Numerical? 

  1.c) Date Time Variables : Handled date-time features

  1.d) Plotting the relationship between yearsold and saleprice

  1.e) Discrete Variables : Extracting the discrete variables
  
  1.f) Finding the relationship between the discrete variables and saleprice
  
  1.g) Continuous Variables: Extracting the continuous variables
  
  1.h) Analyzing the distribution of the Numerical Variables
  
  1.i) Outliers : Figuring out the outliers
  
  1.j) Categorical Variables: Extracting the categorical variables
  
  1.k) Unique: Figuring out unique categories in each categorical feature


2. Feature Engineering
Missing values Categorical : Filling up the null values with 'Missing' name

Missing values Numerical: Replaced the missing values by using median, Created a new feature to capture nan values

DateTime : Taking the dates and subtracting it from SoldYear

Skewed Data : Handled skewed data by using log transform

Rare Categorical Features category: Grouping the categories in each features with < 0.01 into a new categor called Rare_var

Feature Scaling: Standarise the values of the variables to the same range




3. Feature Selection
4. 
Used Lasso Regression model

Used selectFromModel object from sklearn to select the features which coefficients are non-zero

total features: 82 ,selected features: 21 , features with coefficients shrank to zero: 61
