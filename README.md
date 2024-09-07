## Rainfall Prediction Using Linear Regression

# Project Overview:-
This project predicts rainfall levels using historical weather data through a linear regression model. The model takes meteorological features like temperature, humidity, and wind speed to estimate the precipitation in inches. It was implemented using Python and scikit-learn.

# Problem Statement:-
Accurate rainfall prediction is essential for many sectors, including agriculture and disaster preparedness. This project builds a model to predict rainfall based on historical weather features.

# Data:-
The dataset consists of the following weather features:

Temperature (Fahrenheit)
Dew Point (Fahrenheit)
Humidity (%)
Visibility (Miles)
Sea Level Pressure (Inches)
Wind Speed (MPH)
The target variable is precipitation (in inches).

# Methodology:-
 Data Preprocessing: Handled any missing or null values. Normalized or scaled the data where required.Split the dataset into training and testing sets.
 Feature Selection: The following features were selected for building the model: Temperature, Dew Point, Humidity, Visibility, Sea Level Pressure,Wind Speed

# Modeling:- 
Linear regression was applied to predict rainfall levels using the selected features.The model was trained using Python’s scikit-learn library.

# Results:-
The model successfully predicts rainfall levels based on the input features. However, further analysis or improvements might be required to assess its real-world performance, such as implementing evaluation metrics or using more advanced models.
