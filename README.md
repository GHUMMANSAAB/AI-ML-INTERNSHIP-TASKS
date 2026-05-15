# AI-ML-INTERNSHIP-TASKS
# Iris dataset
# What the task was trying to achieve?

The purpose of this task was to build a Machine Learning model that can classify different types of iris flowers based on their physical measurements. The goal was to train a model using features like sepal length, sepal width, petal length, and petal width, and then predict the flower species automatically.

# Which dataset you used?

I used the Iris dataset stored in the CSV file:
iris.csv
The dataset contains measurements of iris flowers and includes the following columns:
•	sepal_length
•	sepal_width
•	petal_length
•	petal_width
•	species
The target column was:
species
which represents the flower type.

# Which models you applied?

I applied two Machine Learning classification models:
DecisionTreeClassifier
RandomForestClassifier

# The main results and what you found?

The dataset was successfully cleaned, visualized, and divided into training and testing data using:
train_test_split()
Graphs such as scatter plots, histograms, and box plots were used for Exploratory Data Analysis (EDA) to understand the dataset patterns.
After training the models:
•	The Decision Tree model achieved high accuracy.
•	The Random Forest model achieved even better accuracy and produced more reliable predictions.
The models were able to correctly classify iris flower species using flower measurements. The project demonstrated how Machine Learning classification models can learn patterns from data and make accurate predictions.

# 2 yfinance dataset

# What the task was trying to achieve?

The purpose of this task was to build a Machine Learning model that can predict future stock closing prices using historical stock market data. The task focused on understanding time-based financial data and using regression models to estimate stock prices.
The goal was to use features such as opening price, highest price, lowest price, and trading volume to predict the stock’s closing price.

# Which dataset you used?

The dataset used in this project was Apple stock market data downloaded from Yahoo Finance using the:
yfinance
library.
The stock symbol used was:
AAPL
The dataset included the following columns:
•	Open
•	High
•	Low
•	Close
•	Volume
The target variable used for prediction was:
Close
which represents the stock closing price.

# Which models you applied?

Two regression models were used in this project.
LinearRegression
RandomForestRegressor

# The main results and what you found?

The stock data was successfully downloaded and explored using statistical summaries and visualizations.
The dataset was split into:
•	80% training data
•	20% testing data
using:
train_test_split()
The models were trained to predict stock closing prices.
The prediction performance was evaluated using:
Mean Absolute Error (MAE)
which measures the average prediction error.
Graphs were created to compare:
•	Real stock prices
•	Predicted stock prices
The results showed that:
•	Linear Regression worked well for simple trends.
•	Random Forest Regressor provided better predictions for complex stock market patterns.
•	Machine Learning models can learn historical stock price behavior and make future price predictions, although stock prices remain highly unpredictable due to market conditions.

# 3 heart disease dataset

# What the task was trying to achieve?

The objective of this task was to build a Machine Learning model that can predict the risk of heart disease using patient health information. The task focused on medical data analysis, classification techniques, and evaluating model performance using different metrics.
The goal was to identify whether a patient has heart disease risk based on features such as age, sex, chest pain type, blood pressure, cholesterol level, and other medical measurements.

# Which dataset you used?

The dataset used in this project was:
heart_disease_uci.csv
This dataset contains patient medical information related to heart disease prediction.
Some important features included:
•	age
•	sex
•	cp (chest pain type)
•	trestbps
•	chol
•	thalch
•	oldpeak
•	dataset
The target column used for prediction was:
num
which represents the heart disease category or risk level.

# Which models you applied?

The main Machine Learning model used in this project was:
Logistic Regression

# The main results and what you found?

The Logistic Regression model successfully learned patterns from the medical dataset and predicted heart disease risk categories.
The project demonstrated that:
•	Proper preprocessing improves model performance.
•	Medical datasets often require encoding and missing value handling.
•	Logistic Regression can effectively classify heart disease risk.
•	ROC-AUC and confusion matrix provide deeper evaluation beyond simple accuracy.
The final model was able to classify patient heart disease risk with good performance using health-related features.

# 4 health question chatbot 

# What the task was trying to achieve?

The aim of this task was to build a Machine Learning system that can predict heart disease risk using patient health information. The project focused on understanding medical data and training a model to identify whether a person may have heart disease or not.

# Which dataset you used?

The dataset used in this project was the:
Heart Disease UCI Dataset
This dataset contains patient health records such as age, sex, chest pain type, blood pressure, cholesterol, and other medical features related to heart disease prediction.

# Which models you applied?

In this project, the main Machine Learning model used was:
Logistic Regression
This model was trained to classify and predict heart disease risk based on patient data.
Different preprocessing techniques such as:
missing value handling
categorical encoding
one-hot encoding
were also applied before training the model.

# The main results and what you found

The model was successfully trained and tested on medical data. Different evaluation methods such as:

Accuracy Score
Confusion Matrix
ROC-AUC Score

were used to check model performance.
The results showed that the model was able to learn patterns from patient health information and predict heart disease risk with good accuracy. The project also showed the importance of data cleaning and preprocessing in improving Machine Learning model performance.

# 5 mental health support chatbot


