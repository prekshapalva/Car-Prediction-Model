## "Car Prediction Model" - A regression model to offer accurate prediction

Determining whether the listed price of a used car is a challenging task, due to the many factors that drive a used vehicle’s price on the market. The focus of this project is developing a machine learning model that can accurately predict the price of a used car based on its features, in order to make informed purchases.

### :one: Introduction
This project “Car Price Prediction Model” focuses on building a car price prediction system using machine learning with Python. The problem statement is to build a model to predict the car prices of several used cars considering several information about the cars from a particular data set. The dataset used in this project contains information about
used cars listed on [www.cardekho.com](www.cardekho.com).

### :two: Prerequisites
Python and Machine learning knowledge

### :three: Steps to be followed
1. The first step is Data collection, where the car data set that has to be fed accurately to the machine learning model is acquired from the source i.e., [www.cardekho.com](www.cardekho.com). 
2. After which, the data needs to be preprocessed because one cannot feed the raw data to a machine learning algorithm. Thus, to understand the data it needs to undergo some pre-processing steps and this is called Data Preprocessing. 
3. After the data is processed, it will be split into training data and testing data. This step is called the Train Test Split. The splitter data obtained will be used to train the machine learning model. Further, testing or evaluation of the machine learning model with data is done. 
4. The data after the train-test split is fed into the regression model. In this project, two regression models are going to be used. First training of the machine learning model will be done with Linear Regression and then the Lasso Regression model is used. 
5. Later, a comparison of the accuracy score or the error percentage of these models are done so as to see which model performs better to this particular data set.

### :four: Output
The results of the tests for “Car Price Prediction Model” were quantified in the
following terms:
1. Linear regression : A linear regression model is a conditional model in which the output variable is a linear function of the input variables and of an unobservable error term that adds noise to the relationship between inputs and outputs. The output is as follows:
<p align="center">
  <img src="https://github.com/prekshapalva/Car_prediction_model/blob/742ffda3f8e7bb5432b00372946d8de000508616/Output_1.png"> 
</p>
2. Lasso regression : Lasso regression performs L1 regularization, which adds a penalty equal to the absolute value of the magnitude of coefficients. This type of regularization can result in sparse models with few coefficients; Some coefficients can become zero and eliminated from the model. The output is as follows:
<p align="center">
  <img src="https://github.com/prekshapalva/Car_prediction_model/blob/742ffda3f8e7bb5432b00372946d8de000508616/Output_2.png">
</p>

### :five: Conclusion
This project is built using data mining and machine learning approaches. It proposes a scalable framework for cars price prediction along with an efficient machine learning model built by training, testing, and evaluating two ML regressors. Thank you!
