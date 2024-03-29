# SC1015 Mini Project 

## Introduction

This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence).  In the highly competitive music industry, music artists and producers sought to create music that will appeal to the broad audience. One aspect of music production is audio engineering. By analysing and understanding the audio features in popular songs today, music producers will be able to make more informed decisions and increase the likelihood of success of their songs. 

Spotify is a digital music platform that has over 100 million tracks and more than 602 million users worldwide. We will use the dataset from Kaggle, ["Most Streamed Spotify Songs 2023"](https://www.kaggle.com/datasets/nelgiriyewithana/top-spotify-songs-2023/data) for our project.

## Problem Definition

- How can music artists engineer their music to increase the popularity of their songs?
- How can we predict the popularity of a music track in spotify based on its audio features?
- Are we able to predict if a movie is good (rating above 7.2) based on its attributes?
- Which model would be the best to predict it?

## Content
1. [Data Extraction](https://github.com/nicklimmm/movie-analysis/blob/main/data-extraction.ipynb)
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

- <https://developers.themoviedb.org/3/getting-started>
- <https://www.free-powerpoint-templates-design.com/old-style-movie-projector-powerpoint-templates/>
- <https://www.kaggle.com/rafjaa/resampling-strategies-for-imbalanced-datasets>
- <https://alexlenail.me/NN-SVG/index.html>
- <https://www.kdnuggets.com/2016/08/learning-from-imbalanced-classes.html/2>
- <https://arxiv.org/pdf/1608.06048.pdf>
- <https://machinelearningmastery.com/tutorial-first-neural-network-python-keras/>
- <https://towardsdatascience.com/derivative-of-the-sigmoid-function-536880cf918e>
- <https://www.researchgate.net/figure/Calculation-of-Precision-Recall-and-Accuracy-in-the-confusion-matrix_fig3_336402347>
- <https://medium.com/analytics-vidhya/confusion-matrix-accuracy-precision-recall-f1-score-ade299cf63cd>


