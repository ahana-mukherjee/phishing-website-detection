# Phishing Website Detection
Phishing Website Detection by Machine Learning Models (Classification)

## Objective

A phishing website is a common social engineering method that mimics trustful uniform resource locators (URLs) and webpages. The objective of this project is to train machine learning models on the dataset created to predict phishing websites. Both phishing and benign URLs of websites are gathered to form a dataset and from them required URL and website content-based features are extracted. The performance level of each model is measures and compared.

## Models & Training

This data set comes under classification problem, as the input URL is classified as phishing (1) or legitimate (0). The supervised machine learning models (classification) considered to train the dataset in this project are:

1. Decision Tree
2. Random Forest
3. XGBoost

## Results

From the obtained results of the above models, XGBoost Classifier has highest model performance of 98.1%. So the XGBoost model is selected and is saved to the file '[XGBoostClassifier.pickle.dat](https://github.com/ahana-mukherjee/phishing-website-detection/blob/master/XGBoostClassifier.pickle.dat)'
