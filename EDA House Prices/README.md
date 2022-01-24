Building Machine Learning Pipelines: Data Analysis Phase

In this project, I have created Machine Learning Pipelines considering all the life cycle of a Data Science Projects.

Project Name: House Prices: Advanced Regression Techniques

The main aim of this project is to predict the house price based on various features.

Dataset :
https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data

Lifecycle In A Data Science Projects
Data Analysis
Feature Engineering
Feature Selection
Model Building
Model Deployment

1.Data Analysis
Missing Values: How many features have missing values?

Numerical Variables : How many features are Numerical?

Date Time Variables : Handled date-time features

Plotting the relationship between yearsold and saleprice

Discrete Variables : Extracting the discrete variables

Finding the relationship between the discrete variables and saleprice

Continuous Variables: Extracting the continuous variables

Analyzing the distribution of the Numerical Variables

Outliers : Figuring out the outliers

Categorical Variables: Extracting the categorical variables

Unique: Figuring out unique categories in each categorical feature




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
