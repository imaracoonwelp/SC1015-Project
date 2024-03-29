# SC1015 Mini Project 

## Introduction

This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence). In 2021, transportation represented the largest segement, contributing 29% of the overall greenhouse gas emissions in the United States. Within this sector, light-duty vehicles alone were responsible for 58% of these emissions. This presents a significant concern as it has direct implications for environmental issues like climate change. Hence, we will investigate the various factors influencing CO2 emissions across different type of vehicles.

We will use the dataset from Kaggle, ["CO2 Emission by Vehicles"](https://www.kaggle.com/datasets/debajyotipodder/co2-emission-by-vehicles/data) for our project. It details the amount of CO2 emissions by different types of vehicles in Canada and is compiled from [Canada Government Official Open Data Website] (https://open.canada.ca/data/en/dataset/98f1a129-f628-4ce4-b24d-6f16bf24dd64#wb-auto-6).

## Problem Definition

- How can music artists engineer their music to increase the popularity of their songs?
- How can we predict the popularity of a music track in spotify based on its audio features?
- Are we able to predict if a movie is good (rating above 7.2) based on its attributes?
- Which model would be the best to predict it?

## Content
1. [Data Extraction](https://github.com/imaracoonwelp/SC1015-Project/blob/main/Data%20Preparation%20and%20Cleaning.ipynb)
2. [Data Visualization](https://github.com/nicklimmm/movie-analysis/blob/main/data-visualization.ipynb)
3. [Data Resampling and Splitting](https://github.com/nicklimmm/movie-analysis/blob/main/data-resampling-and-splitting.ipynb)
4. [Logistic Regression](https://github.com/nicklimmm/movie-analysis/blob/main/logistic-regression.ipynb)
5. [Neural Network](https://github.com/nicklimmm/movie-analysis/blob/main/neural-network.ipynb)

## Models Used

1. Logistic Regression
2. Neural Networks

## Conclusion

- Popularity and budget have low linear correlation value with ratings (watch out for bandwagons 🤣)
- Popularity of the casts and crews have higher linear correlation value with ratings
- Resampling imbalanced data improved model performance especially on the minority class
- Logistic Regression did not perform well with non-linearly correlated variables
- Neural Networks along with SMOTEENN resampling method consistently did well in predicting good movies after 100 training attempts (around 72% accuracy, 70% recall)
- Yes, it is possible to predict if a movie is good with acceptable amount of accuracy and recall

## What did we learn from this project?

- Handling imbalanced datasets using resampling methods and imblearn package
- Neural Networks, Keras and Tensorflow
- Logistic Regression from sklearn
- API Usage
- Other packages such as tqdm, json, requests
- Collaborating using GitHub
- Concepts about Precision, Recall, and F1 Score

## Contributors

- Chester Chiow (@chesterchiow) - Neural Networks, Data Resampling, Data Extraction
- Eng Yi Xuan (@imaracoonwelp) - Logistic Regression
- Le Xuan Tung (@Lexuantunglego2005) - Data Visualization, Data Extraction

## References

- <https://www.kaggle.com/datasets/debajyotipodder/co2-emission-by-vehicles/data>
- <https://open.canada.ca/data/en/dataset/98f1a129-f628-4ce4-b24d-6f16bf24dd64#wb-auto-6>
- <https://www.epa.gov/greenvehicles/fast-facts-transportation-greenhouse-gas-emissions>
- <https://www.way.com/blog/what-are-cylinders-in-a-car-all-you-need-to-know/>



