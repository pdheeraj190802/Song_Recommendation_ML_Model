# Song_Recommendation_ML_Model

### Introduction
I selected the problem from the kaggle music hakathon . Link from where I downloaded the
dataset: https://www.kaggle.com/c/MusicHackathon/data
This data has ratings given by the listeners, qualitative feedback, answers to the question on music
and listeners demographics. We will use this dataset to get the rating of the test dataset.

#### Problem Statement
Recommendation of a song for the listener based on gender, age, region, artist they like and many more.

It is a Regression type problem.

### Conclusion/Summary

I downloded this dataset from kaggle. Then after I imported the requried python libraries. Now,
I started cleaning the dataset like deleting the rows in which data is missing or substituting the
average value of the column in the missing data. Then to get the insights from the columns of
the dataset, I started to make the visualizations of the dataset. After I got the insights from the
dataset and the relationship betweeen the columns of the dataset I started to make the model.
I used XGBoosta and RFR models. After checking the performances of both the models, I had
come to a conclusion that XGBoost model had high performance than RFR. So, at last I used the
XGBoost model to predict the values of dataset.
