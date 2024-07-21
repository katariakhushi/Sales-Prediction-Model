# Sales-Prediction-Model
## Overview
This project aims to predict sales based on advertising expenditure across different media platforms using machine learning techniques. The dataset contains 200 observations with three variables: TV, Radio, and Newspaper advertising budgets, along with the corresponding sales figures. The model uses linear regression to understand and predict the relationship between advertising spend and sales.

## Approach
1. Data Loading and Exploration
Load the dataset using pandas and inspect its size and first few records.
Display summary statistics to understand the distribution of each variable.
Use df.info() to check the data types and for any missing values.
Visualize the data using boxplots to detect any outliers in the dataset.
2. Handling Missing Values
Check for missing values and ensure that there are none.
3. Exploratory Data Analysis (EDA)
Visualize the relationships between sales and the advertising budgets for TV, Radio, and Newspaper.
Create scatter plots to observe the linear relationship between each advertising medium and sales.
Use a heatmap to visualize the correlation between variables.
4. Data Preparation
Define the predictors (x) and the target variable (y).
Split the data into training and testing sets using train_test_split to allow model validation.
5. Model Building and Evaluation
## Linear Regression Model:

Initialize and fit a linear regression model using the training data.
Predict sales on the test data and evaluate the model using metrics like R-squared, Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).
Visualize the performance by plotting actual vs. predicted sales.
## Cross-Validation:

Perform 10-fold cross-validation to ensure the model's robustness.
Calculate and print cross-validation scores to understand the model's performance across different subsets of the data.
6. Results Compilation
Store the results of the linear regression model, including R-squared, MAE, MSE, RMSE, and the mean cross-validation score, in a DataFrame.
Print the final results for interpretation.
## Conclusion
The model's performance is summarized in the df_results DataFrame, providing insights into the effectiveness of the predictors. The use of cross-validation helps in assessing the model's stability and generalizability to unseen data. The results suggest areas for improvement, possibly by exploring additional features, different modeling techniques, or more complex algorithms.
