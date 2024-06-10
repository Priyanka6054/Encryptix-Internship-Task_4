# SALES PREDICTION USING PYTHON
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
The project is structured as follows:
* data: Directory containing the dataset Advertising.csv.
* notebooks: Jupyter notebooks containing the code for data exploration, visualization, and model building.
* src: Source directory containing Python scripts for loading data, training the model, and evaluation.
* README.md: Project documentation.

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
