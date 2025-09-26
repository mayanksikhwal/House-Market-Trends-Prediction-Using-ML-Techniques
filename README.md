# House-Market-Trends-Prediction-Using-ML-Techniques

## Project Description
This project focuses on building a robust regression model to accurately predict residential house prices. Utilizing the dataset from the Kaggle "House Prices - Advanced Regression Techniques" competition, the project covers a comprehensive machine learning workflow. This includes:

**Data Loading and Initial Inspection:** Loading the training and testing datasets and performing initial checks on their structure and content.

**Exploratory Data Analysis (EDA):** Deep diving into the data to understand the distribution of the target variable (SalePrice), identifying correlations between features, and visualizing key relationships. A significant part of this involves handling the skewness of the target variable through log transformation.

**Data Preprocessing:** This is a crucial step involving:

&bull; Handling missing values using appropriate imputation strategies based on feature types (numerical vs. categorical) and their characteristics.

&bull; Engineering new, potentially more informative features from existing ones (e.g., total square footage, total bathrooms, house age).

&bull; Encoding categorical variables using techniques like one-hot encoding to make them suitable for machine learning models.

**Model Building:** Training and evaluating different regression models. The project demonstrates a baseline Linear Regression model and a more advanced XGBoost model, a powerful gradient boosting algorithm known for its performance on structured data.

**Model Evaluation:** Assessing the performance of the trained models using standard regression metrics such as Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), and R-squared.

**Submission File Generation:** Using the best-performing model to make predictions on the unseen test data and formatting the predictions into a submission file for the Kaggle competition.

## Tech Stack
The project is implemented using Python and leverages the following libraries:

**pandas:** For data manipulation and analysis.

**numpy:** For numerical operations, particularly for handling arrays and mathematical functions (like log transformation).

**matplotlib and seaborn:** For data visualization and creating informative plots.

**scipy:** Used for statistical functions.

**scikit-learn:** A comprehensive library for machine learning, used here for model selection, preprocessing (scaling), and evaluation metrics.

**xgboost:** A highly efficient gradient boosting library used for building the advanced regression model.

**kaggle API:** Used to directly download the competition dataset.

## How to Run
To run this project, follow these steps:

**1. Clone the repository:** If this notebook is part of a larger repository, clone it to your local machine or Google Drive.

**2. Install dependencies:** Make sure you have Python installed. Install the required libraries using the requirements.txt file. You can generate this file using the provided code cell or manually create it with the libraries listed in the "Tech Stack" section. 
