# Phishing-Scam-Detector-Analysis
Created by: Mia O'Halloran, Nicholas Dias, Jiayi Shen, Kaylee Dong

Python analysis of whether a phishing scam can be detected by it's URL contents. Used supervised machine learning (K Nearest Neighbors and Random Forest Classifiers) from Scikit-Learn to classify URLS as non-phishing or phishing based on certain features, including URL parameters, path level, and security protocol. Using NumPy and Matplotlib, we analyzed the dataset using t-tests, and correlations as well as visualizing data through graphs such as random forests feature importance, percentage bar chart, box plot, correlation scatter plots, histograms and violin plots.

Conclusion:
From our machine learning models, random forest classifier was a moderate to high predictor of phishing or non phishing URLs with an accuracy rate of over 80%, but the KNN model was a low predictor. We found some strong correlations in features, but they were similar between the different URL types. 

Utilized Dataset: “Dataset phishing - dataset to find out phishing attacks on websites”  via https://www.kaggle.com/datasets/simaanjali/phising-detection-dataset/data 

BU DS110, Spring 2024
