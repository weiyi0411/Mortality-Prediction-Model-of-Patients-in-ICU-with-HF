# Mortality-Prediction-Model-of-Patients-in-ICU-with-HF
 This research targets the mortality prediction modeling of intensive care units  (ICUs)-admitted heart failure (HF) patients.


 We started this project with data extraction through Google big query. Then we
 processed the raw data to a clear dataset using methods including one-hot encoding
 and missing data supplementation. To reduce the dimensions, we selected the most
 important 11 features using eXtreme Gradient Boosting (XGBoost). For the modeling
 part, we applied 4 classification models, Decision Tree (DT), Random Forest (RF),
 Gradient Boosting (GB), and XGBoost, with the combination of hyperparameter
 tuning and cross-validation. The result shows RF has the best performance with the
 AUCreaching 0.83 and the accuracy reaching 0.75
