# NYC Airbnb Review Prediction

This project aims to predict the number of reviews for Airbnb listings in New York City using various machine learning models, including Linear Regression, Decision Trees, and Random Forest.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Data Preprocessing](#data-preprocessing)
- [Models](#models)
  - [Linear Regression](#linear-regression)
  - [Decision Trees](#decision-trees)
  - [Random Forest](#random-forest)
- [Results](#results)
- [Conclusion](#conclusion)
- [What I Learned](#what-i-learned)
- [Usage](#usage)
- [Installation](#installation)
- [License](#license)

## Introduction
The purpose of this project is to build machine learning models to predict the number of reviews for Airbnb listings in New York City. Accurate predictions can help hosts and property managers optimize their listings and improve customer satisfaction.

## Dataset
The dataset used in this project is the [New York City Airbnb Open Data](http://insideairbnb.com/get-the-data.html). It contains detailed information about Airbnb listings in NYC, including the number of reviews, price, location, and other relevant features.

## Data Preprocessing
The data preprocessing steps include:
- Handling missing values
- Encoding categorical variables
- Normalizing numerical features
- Splitting the data into training and testing sets

## Models

### Linear Regression
Linear Regression is a simple and interpretable model that attempts to predict the target variable by fitting a linear relationship between the input features and the target.

### Decision Trees
Decision Trees model the data by splitting it into subsets based on the value of input features, forming a tree-like structure. This model is easy to interpret and can capture non-linear relationships.

### Random Forest
Random Forest is an ensemble method that builds multiple decision trees and combines their predictions. This approach improves the model's accuracy and reduces the risk of overfitting.

## Results
The performance of each model is evaluated using metrics such as Root Mean Squared Error (RMSE) and R-squared (R²). Here are the results:

- **Linear Regression**:
  - RMSE: 43.37
  - R²: 0.300
- **Decision Trees**:
  - RMSE: 28.18
  - R²: 0.705
- **Random Forest**:
  - RMSE: 23.08
  - R²: 0.802

## Conclusion
The Random Forest model performed the best among the three models, demonstrating the highest accuracy in predicting the number of reviews. However, each model has its own strengths and can be chosen based on specific requirements.

## What I Learned
- Data preprocessing techniques are crucial for preparing the dataset for modeling.
- The importance of evaluating different models to find the best one for the task.
- The trade-offs between model complexity and interpretability.

## Usage
To use the models in this project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/nyc-airbnb-review-prediction.git
   ```
2. Navigate to project directory:
   ```bash
   cd NY_airbnb_reviews
   ```
3. install the required dependences
4. Run jupyter notebook to see analysis and model training:
   ```bash
   jupyter notebook
   ```
## Installation
Ensure you have Python 3.7+ and the following libraries installed:
	•	pandas
	•	numpy
	•	scikit-learn
	•	matplotlib
	•	seaborn

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
