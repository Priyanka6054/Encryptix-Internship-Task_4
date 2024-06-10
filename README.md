# Sales Prediction
## Project Overview
This project involves predicting the amount of sales based on advertising expenditure. Using a dataset that includes advertising spending across TV, radio, and newspapers, a linear regression model is built to forecast future sales. This project aims to help businesses optimize their advertising strategies to maximize sales potential.

## Dataset Overview
* The dataset used in this project is named Advertising.csv. It contains the following columns:
  - TV: Advertising spend on TV 
  - Radio: Advertising spend on Radio 
  - Newspaper: Advertising spend on Newspaper 
  - Sales: Sales 
The dataset provides a foundation to understand how different advertising channels contribute to sales.

## Project Structure
The project is organized as follows:
### 1. Data Collection:
* Loading the dataset using Pandas.
* Initial exploration to understand the data structure and check for null values.
### 2. Feature Scaling
- Ensure the features are on a similar scale, if necessary. For linear regression, feature scaling is not always required.
### 3. Data Preprocessing
- Clean and preprocess the data as needed. For this dataset, no major preprocessing is required other than handling the data types correctly.
### 4. Visualization
- Visualize the dataset to understand the relationships between different features and the target variable.
### 5.Data Splitting
- Split the data into features (X) and target (y), then into training and testing sets.
### 6. Model Training
- Train a linear regression model using the training data.
### 7. Model Evaluation
- Evaluate the model's performance using the testing data and visualize the results.

## Libraries Used
The following Python libraries are used in this project:
* pandas: For data manipulation and analysis.
* numpy: For numerical computations.
* matplotlib: For data visualization.
* seaborn: For statistical data visualization.
* scikit-learn: For building and evaluating the machine learning model.
  
## Results
The linear regression model built in this project achieved the following performance metrics:
* Mean Squared Error (MSE): 2.907756910271091
* R^2 Score: 0.9059011844150826

The model's predictions closely matched the actual sales, as demonstrated in the scatter plot of actual vs. predicted sales. The feature importance plot indicated the relative contribution of TV, radio, and newspaper advertising spend to sales.

## Conclusion
This project demonstrates the application of linear regression for sales prediction based on advertising expenditure. By analyzing the data and building a predictive model, we can make informed decisions on how to allocate advertising budgets across different channels to maximize sales. The results show that TV and radio advertising have a significant impact on sales, while newspaper advertising has a lesser effect.
