# SC1015 Mini Project 

## Introduction

This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence). In 2021, Canada's total greenhouse gas emissions were 670 megatonnes of carbon dioxide equivalent (Mt CO2 eq), a 1.8% increase from 2020. Transportation represented the second largest segement, contributing 22% of the overall greenhouse gas emissions in Canada. Within this sector, light-duty vehicles, such as passenger cars and minivans, alone were responsible for almost half of these emissions. This presents a significant concern as it has direct implications for environmental issues like climate change. Hence, we will investigate the various factors influencing CO2 emissions across different types of vehicles.

We will use the dataset from Kaggle, ["CO2 Emission by Vehicles"](https://www.kaggle.com/datasets/debajyotipodder/co2-emission-by-vehicles/data) for our project. It details the amount of CO2 emissions by different types of vehicles in Canada and is compiled from [Canada Government Official Open Data Website](https://open.canada.ca/data/en/dataset/98f1a129-f628-4ce4-b24d-6f16bf24dd64#wb-auto-6).

## Problem Definition

- How can we predict the amount of CO2 emissions of a vehicle based on its specifications?
- Which model would be the best to predict it?

## Content
1. [Data Extraction](https://github.com/imaracoonwelp/SC1015-Project/blob/main/Data%20Extraction%20and%20Cleaning.ipynb)
2. [Exploratory Data Analysis](https://github.com/imaracoonwelp/SC1015-Project/blob/main/Exploratory%20Data%20Analysis.ipynb)
3. [One-Hot Encoding](https://github.com/imaracoonwelp/SC1015-Project/blob/main/One%20Hot%20Encoding.ipynb)
4. [Linear Regression Model](https://github.com/imaracoonwelp/SC1015-Project/blob/main/Linear%20Regression%20Models.ipynb)
5. [Other Regression Models](https://github.com/imaracoonwelp/SC1015-Project/blob/main/Other%20Regression%20Models.ipynb)

## Models Used

1. Linear Regression
2. Random Forest for Regression
3. K-Nearest Neighbour Regression

## Conclusion

- Number of Gears and CO2 Emission have low correlation value, does not have a linear relationship with CO2 Emission
- Fuel Consumption and CO2 Emission have the highest correlation value
- 
- Popularity and budget have low linear correlation value with ratings (watch out for bandwagons 🤣)
- Popularity of the casts and crews have higher linear correlation value with ratings
- Resampling imbalanced data improved model performance especially on the minority class
- Logistic Regression did not perform well with non-linearly correlated variables
- Neural Networks along with SMOTEENN resampling method consistently did well in predicting good movies after 100 training attempts (around 72% accuracy, 70% recall)
- Yes, it is possible to predict if a movie is good with acceptable amount of accuracy and recall

## What did we learn from this project?

- Collaborating using GitHub
- Using Z-Score method to remove outliers
- Identifying clusters in Joint Plots
- One-Hot Encoding
- Linear Regression
- Random Forest for Regression 
- Hyperparameters Tuning for Random Forest for Regression using GridSearchCV
- K-Nearest Neighbour Regression
- Hyperparameters Tuning for K-Nearest Neighbour Regression using GridSearchCV
- Concepts on R^2 and MSE

## Contributors

- Chester Chiow (@chesterchiow) - Data Preparation and Cleaning, Exploratory Data Analysis, K-Nearest Neighbour Regression Model
- Eng Yi Xuan (@imaracoonwelp) - One Hot Encoding, Linear Regression Model 
- Le Xuan Tung (@Lexuantunglego2005) - Random Forest for Regression

## References

- <https://www.kaggle.com/datasets/debajyotipodder/co2-emission-by-vehicles/data>
- <https://www.canada.ca/en/environment-climate-change/services/environmental-indicators/greenhouse-gas-emissions.html>
- <https://www.way.com/blog/what-are-cylinders-in-a-car-all-you-need-to-know/>
- <https://www.analyticsvidhya.com/blog/2022/08/dealing-with-outliers-using-the-z-score-method/>
- <https://saturncloud.io/blog/linear-regression-with-sklearn-using-categorical-variables/#:~:text=To%20use%20categorical%20variables%20in,label%20encoding%2C%20and%20binary%20encoding.>
- <https://towardsdatascience.com/random-forest-regression-5f605132d19d>
- <https://www.analyticsvidhya.com/blog/2018/08/k-nearest-neighbor-introduction-regression-python/>



