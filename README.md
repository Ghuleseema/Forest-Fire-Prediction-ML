# Forest-Fire-Prediction-ML
Machine Learning project to predict forest fires using weather data
About The Project:
Using Data Science and Machine learning, we can build a model that takes in the detected fires dataset learns and detects future fires based on certain Weather report.
Storing the Sourced dataset to MongoDB.
Building a Flask App hosted on Heroku.
Sklearn for pre-processing and Model Building
Pandas, Numpy, Matplotlib for csv reading, Data Processing, Data Cleaning, Visualization etc.
Steps:
Installing Python, PyCharm, Monogodb, Git to Computer.
Download the source dataset from UCI Repository.
For Classification algorithm decided to predict the features Classes from the dataset which is Binary classification (fire, not fire).
For Regression Problem algorithm decided to predict the feature FWI (Fire weather Index) which is 90%+ correlated to Classes Feature.
Loading CSV and Inserting to DB
The Downloaded CSV file is loaded as pandas Dataframe using Pandas Library.


EDA:
In this step, we will apply Exploratory Data Analysis (EDA) to extract insights from the data set to know which features have contributed more in predicting Forest fire by performing Data Analysis using Pandas and Data visualization using Matplotlib & Seaborn.
It is always a good practice to understand the data first and try to gather as many insights from it.
Model Building:
For Regression Problem algorithm decided to predict the feature FWI (Fire weather Index) which is 90%+ correlated to Classes Feature.
Models used : Linear regression, Lasso Regression, Ridge Regression, Random forest, Decision tree, K-Nearest Neighbour regressor, Support Vector Regressor:
For Classification algorithm decided to predict the features Classes from the dataset which is Binary classification (fire, not fire).
Models used : Logistic Regression, Decision Tree, Random Forest, XGboost, K-Nearest Neighbour.
Model Selection:
HyperParameter Tuning Randomized Gridsearch CV is done for top 2 models for both Regression and Classification.
For Classification Stratified Kfold Cross-Validation metrics is used based best Mean CV Accuracy Model is used for Model Deployment.
For Regression R2 score metrics is used to select best model The R2 score is one of the performance evaluation measures for regression-based machine learning models.

Screenshots:
<img width="1920" height="1080" alt="Screenshot 2026-03-16 235700" src="https://github.com/user-attachments/assets/fd3a4ae6-9820-4de9-927c-b6edbe623f73" />


