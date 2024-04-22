# UFC Fighter Analytics

Welcome to the UFC Fighter Analytics project repository! This project focuses on analyzing data related to Ultimate Fighting Championship (UFC) fighters, exploring various aspects of their statistics, styles, and trends.

## Data Source
The data used in this project is sourced from the [UFC Fighters Statistics dataset on Kaggle](https://www.kaggle.com/datasets/aaronfriasr/ufc-fighters-statistics). Please refer to the dataset link for more information about its contents and usage terms.

## Project Overview

This project consists of three main notebooks:

### 1. cleaning_and_analysing.ipynb

In this notebook, the data is cleaned and analyzed. Here are the main steps:

- Data Cleaning: Handling missing values, duplicates, and outliers.
- Exploratory Data Analysis (EDA): Visualizing distributions and correlations among different fighter statistics.
- Feature Engineering: Creating new features such as win percentage and weight class based on existing data.

### 2. data_preparation.ipynb

This notebook focuses on preparing the data for modeling. Key steps include:

- Standardization: Scaling numerical features using StandardScaler.
- Encoding Categorical Features: One-hot encoding categorical features to convert them into a format suitable for modeling.
- Splitting Data: Dividing the dataset into training and testing sets for model evaluation.

### 3. modeling.ipynb

In this notebook, machine learning models are built and evaluated. The main models used are Linear Regression and XGBoost. The evaluation metrics used are Mean Squared Error (MSE) and R-squared. Here are the results obtained:

- Linear Regression:
    - MSE: 0.0062
    - R-squared: 0.4457

- XGBoost:
    - MSE: 0.0048
    - R-squared: 0.5728

## Conclusion

The project aims to predict the win percentage of UFC fighters based on their physical characteristics and other statistics. The chosen models provide insights into the factors influencing fighter performance and can be further refined for more accurate predictions.

Feel free to explore the notebooks for more details and insights!

## Contributions

Contributions to this project are welcome! If you have any suggestions, ideas, or improvements, feel free to open an issue or submit a pull request. Let's collaborate to enhance our understanding of UFC fighter analytics!
