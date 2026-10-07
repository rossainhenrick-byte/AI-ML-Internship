# House Price Prediction Model

## Project Overview

This mini project focuses on predicting house prices using a **Linear Regression** machine learning model.

The project uses a housing dataset containing information about different properties. The categorical features are converted into numerical form, and the dataset is divided into training and testing sets.

## Objective

The main objectives of this project are:

* Train a Linear Regression model.
* Predict house prices.
* Evaluate the model using the R² score.
* Compare actual and predicted house prices using visualizations.
* Plot a Linear Regression trend line.

## Dataset

**Dataset:** House Prices Dataset

The dataset contains information about houses, including features such as:

* Area
* Number of bedrooms
* Number of bathrooms
* Number of stories
* Parking
* Furnishing status
* Main road
* Guest room
* Basement
* Air conditioning
* Preferred tenant
* Locality rating
* Price

The target variable is:

**Price**

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook

## Project Workflow

The project follows these steps:

1. Import the required Python libraries.
2. Load the housing dataset.
3. Explore the dataset.
4. Convert categorical variables into numerical values using one-hot encoding.
5. Separate the features and target variable.
6. Split the dataset into training and testing data.
7. Train the Linear Regression model.
8. Predict house prices using the test data.
9. Calculate the R² score.
10. Visualize actual vs predicted house prices.
11. Add a Linear Regression trend line.
12. Analyze the results.

## Model Used

### Linear Regression

Linear Regression is a supervised machine learning algorithm used to predict a continuous numerical value.

In this project, Linear Regression is used to predict the **price of houses** based on the available property features.

## Model Evaluation

The model is evaluated using the **R² (R-squared) score**.

The obtained R² score is approximately:

**0.653**

This means that the model explains approximately **65.3% of the variation in house prices**.

## Visualizations

Two visualizations are included in the project:

### 1. Predicted vs Actual House Prices

This scatter plot compares the actual house prices with the prices predicted by the Linear Regression model.

### 2. Predicted vs Actual with Regression Trend Line

A Linear Regression trend line is added to visualize the overall relationship between actual and predicted house prices.

## Conclusion

In this project, a Linear Regression model was developed to predict house prices using the housing dataset. The categorical data was converted into numerical form, and the dataset was divided into training and testing sets.

The model successfully predicted house prices, and its performance was evaluated using the R² score. The predicted and actual house prices were also visualized using scatter plots, including a regression trend line.

The model achieved an R² score of approximately **0.653**, which means that the model explains about **65.3% of the variation in house prices**.

Overall, this project demonstrates how **Linear Regression can be used for house price prediction**.

## Files in This Project

* `House_Price_Prediction.ipynb` — Jupyter Notebook containing the complete project.
* `Housing.csv` — Housing dataset used for prediction.
* `Titanic-Dataset.csv` — Dataset file included in the project folder.
* `archive (5).zip` — Dataset archive.

## Author

**Rossane Henrick**
