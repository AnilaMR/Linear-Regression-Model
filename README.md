# Predicting Sales Based on Advertising Spend
### Project Overview
This project uses a simple linear regression model to predict sales based on advertising expenditure. The dataset contains advertising spend across three major media channels: TV, Radio, and Newspaper, along with the corresponding sales figures. Our primary focus is to analyze the impact of TV advertising spending on sales and to develop a predictive model to help businesses optimize their advertising budgets.
### Table of Contents
- Project Overview
- Dataset
- Aim
- Exploratory Data Analysis (EDA)
- Model Building
- Results and Evaluation
- Visualization
- Technologies Used
## Dataset
The dataset used in this project consists of 200 observations and 4 variables:
1. TV: Advertising spend on TV (in thousands of dollars).
2. Radio: Advertising is spent on radio (in thousands of dollars).
3. Newspaper: Advertising is spent on newspapers (in thousands of dollars).
4. Sales: Sales generated (in thousands of units).
## Aim
The aim of this project is to:
1. Analyze the relationship between advertising expenditure and sales.
2. Build a predictive model using linear regression to forecast sales based on TV advertising spend.
3. Evaluate the model's performance and visualize the fit using a regression line.
## Exploratory Data Analysis (EDA)
We begin by exploring the dataset:
- Summary statistics of the data.
- Checking for missing values.
- Visualizing the relationships between variables using pair plots and correlation heatmaps.
## Model Building
- Linear Regression is used to predict sales based on TV advertising spend.
- The dataset is split into training and testing sets (80% training, 20% testing).
- We evaluate the model using metrics such as Mean Squared Error (MSE) and the R² score.
## Results and Evaluation
- Mean Squared Error (MSE): The average squared difference between the actual and predicted sales values.
- R² Score: A measure of how well the model explains the variance in sales.
## Visualization
A scatter plot is used to visualize the actual sales values, while the regression line represents the model's predictions. This helps demonstrate how well the model fits the data and how sales vary with TV advertising spend. 
### Technologies Used
- Python: Programming language used for the implementation.
- Libraries:
  - pandas: For data manipulation and analysis.
  - numpy: For numerical computations.
  - matplotlib & seaborn: For data visualization.
  - scikit-learn: For machine learning and model building.
  
