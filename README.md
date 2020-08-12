# Sentiment-analysis-using-DistillBERT-and-ktrain
Repo for sentiment analysis on IMDB movie review dataset using DistillBERT

1. Built a text classification model that can be used for predicting user reviews using DistillBert transformer.
2. Dataset used contains two classes.
3. Positive and negative sentiment are the two classes.
4. Used ktrain for preprocessing and training the text data.
5. Trained and saved the model with prediction result of 94% accuracy.
6. Deployed the model as web aplication using flask framework.

## Code and Resources Used

Python Version: 3.7

Tensorflow version: 2.1.0

Packages: pandas, numpy, tensorflow, ktrain, flask

ktrain implementation reference : Laxmi kant

### Dataset Structure

* Two folders

1. Train: 25000 reviews
2. Test: 25000 reviews

## Model deployment using Flask
* Using the flask framework, the model was deployed in web application.
* Model can be deployed using 'flask_DistillBERT_ktrain.py'

![alt text](https://github.com/Jishan-works/Covid-19-Xray-classification-RESNET50-flask-deployment-/blob/master/positive_prediction.png)

