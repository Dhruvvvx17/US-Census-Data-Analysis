# US-Census-Data-Analysis

This is a simple data analysis project on the US Census data obtained from the UCI Machine Learning Repository.

Link to the dataset can be found here: https://archive.ics.uci.edu/ml/datasets/Adult

The project is a binary classification - given certain details of an individual, does his/her income fall under 50K USD or over 50K USD.

The attributes include:
1. age: continuous
2. workclass: categorical (8 distinct classes)
3. fnlwgt: continuous.
4. education: categorical (16 distinct classes)
5. education-num: continuous.
6. marital-status: (7 distinct classes)
7. occupation: categorica (14 distinct classes)
8. relationship: categorical (6 distinct classes)
9. race: categorical (5 distinct classes)
10.sex: categorica (2 distinct classes)
11. capital-gain: continuous.
12. capital-loss: continuous.
13. hours-per-week: continuous.
14. native-country: categorical (41 distinct classes)

There are a total of 48842 instances with a few '?'/NaN values that have been handled in this project.

The project performs the following:
1. data cleaning - Missing value/NaN value handling
2. in depth feature understanding (using plots)
3. chi2 test to rank feature importance to target class
4. feature correlation
5. feature selection
6. categorical to numerical feature conversion
7. standardization
8. random forest model - with gridsearchCV to find the best set of hyperparameters
9. K-nearest neighbors - with gridsearchCV to find the best set of hyperparameters followed by K-crossfold validation
10. comparison of accuracy, precision, recall and F1-score.
