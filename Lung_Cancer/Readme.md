# Problem:
Required faster prediction to avoid any casualities.
1. Lung cancer has multiple symptoms that we can used to predict whether a person has Lung cancer or Not.
2. Purpose is to train machine learning model for disease prediction based on symptoms.
# Binary classification problem
1. Cancer -> Yes,No
2. dataset: https://www.kaggle.com/datasets/ajisofyan/survey-lung-cancer

## Lib/model used
1. Pandas
2. Label_Encoder
3. Xgboost classifier : boosting Algo
4. Sklearn
5. permutation_importance

## Results
   | class  | precision|    recall | f1-score|   support|
   ----------|---------|-----------|---------|----------|
   |       0 |      0.83 |     0.71|      0.77 |        7|
   |        1 |      0.98|      0.99 |     0.98 |       95
   
   | accuracy| 0.97  |
   |---------|-------|




