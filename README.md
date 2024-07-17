## Introduction
## Preprocess
## EDA
## Feature Engineering
## Model 
Evaluation on validation data
| Model              | Recall     | Precision  | Accuracy  |
|--------------------|------------|------------|-----------|
| Random forest      | 61.23%     | 78.27%     | 93.64%    |
| XGBoost            | 57.75%     | **82.06%**  | **93.76%** |
| Logistic Regression| **85.44%** | 48.01%     | 87.82%    |

## Interpret
![image](https://github.com/user-attachments/assets/132423f7-c6d1-4804-83eb-efcd2288bfbd)
Among the three models we built with their features important, it's clear that the genre of a song has the most significant impact on its popularity. In each model, songs with the Pop genre stood out as having the greatest influence on popularity. This makes sense, as Pop songs are inherently designed to be popular.
