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

### Data Driven Insights¶
Drawing back to our problem definition, "How can we predict the amount of CO2 emission of a vehicle based on its specfications?".

Firstly, yes, we can predict the amount of CO2 emission of a vehicle based on its specfications. We identified that Fuel Comsumption Comb is the most significant factor when determining the CO2 emissions. There is a significant correlation between Fuel Consumption Comb and both Cylinders and Engine Size. This suggests that Cylinders and Engine Size play important roles in determining fuel consumption, which subsequently affects CO2 emissions. Fuel type is also observed to have influence over the relationship between CO2 emissions and Fuel Consumption Comb. For the same amount of Fuel Consumption Comb, Diesel emits most CO2 while Ethanol emits the least.

Secondly, to answer the question "How?", we applied various regression models to predict CO2 emissions. Among the models explored—Linear Regression, Random Forest for Regression, and K-Nearest Neighbor Regression—Random Forest for Regression emerged as the most effective. This model outperformed others by considering non-linear relationships and demonstrating lower susceptibility to overfitting.

### Recommendations
To minimise environmental impact, vehicle manufacturers should prioritize efforts to reduce fuel consumption, as it directly impacts CO2 emissions. To achieve this, they should focus on strategies to lower the number of cylinders and engine size in vehicles. Recognizing the significant impact of fuel type on emissions, manufacturers should also consider the choice of fuel in vehicle design.

While reducing fuel consumption and considering fuel types are critical goals for minimizing environmental impact, vehicle manufacturers must also consider other factors such as vehicle performance, functionality, and intended use. Balancing these considerations is essential for designing vehicles that meet the diverse needs and preferences of consumers while also promoting sustainability.

## What did we learn from this project?

- Collaborating using GitHub
- Using Z-Score method to remove outliers
- Identifying clusters in Joint Plots
- One-Hot Encoding
- Univariate and Multivariate Linear Regression
- Random Forest for Regression 
- Cross-Validation for Random Forest for Regression using GridSearchCV
- K-Nearest Neighbour Regression
- Cross-Validation for K-Nearest Neighbour Regression using GridSearchCV
- Concepts on R^2, Adjusted R^2 and MSE

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
- <https://towardsdatascience.com/a-quick-and-dirty-guide-to-random-forest-regression-52ca0af157f8>
- <https://www.analyticsvidhya.com/blog/2018/08/k-nearest-neighbor-introduction-regression-python/>



