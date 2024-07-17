## Introduction
## Preprocess
## EDA
## Feature Engineering
Transform categorical data
Creating new features whose correlation score > 0.2 or < -0.2 based on the figure below
![image](https://github.com/user-attachments/assets/a4da15d1-8ba0-49dc-a5c5-d1cf6e35f9f5)
Some new created features with their correlation score with target column
| New Features           | Correlation score |
|------------------------|-------------------|
| acousticness\_loudness | 0.166             |
| danceability\_energy   | 0.149             |
| loudness\_tempo        | 0.145             |


## Model 
Evaluation on validation data
| Model              | Recall     | Precision  | Accuracy  |
|--------------------|------------|------------|-----------|
| Random forest      | 61.23%     | 78.27%     | 93.64%    |
| XGBoost            | 57.75%     | **82.06%**  | **93.76%** |
| Logistic Regression| **85.44%** | 48.01%     | 87.82%    |

Based on the results, the Logistic Regression model had the highest recall (85.44%), while the XGBoost model had the highest precision (82.06%) and the highest accuracy (93.76%).

## Interpret
![image](https://github.com/user-attachments/assets/132423f7-c6d1-4804-83eb-efcd2288bfbd)
Among the three models we built with their features important, it's clear that the genre of a song has the most significant impact on its popularity. In each model, songs with the Pop genre stood out as having the greatest influence on popularity. This makes sense, as Pop songs are inherently designed to be popular.
