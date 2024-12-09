# Prices Forecast Lab

## Introduction

This lab work was made during the course of Applied Artificial Intelligence at ITMO University. Its goal was to predict the housing prices by using neural network regression model made by TensorFlow Keras.

## Used Tools & Libraries

*  Python
*  Google Colab (CPU, T4 GPU) & Jupiter Notebook
*  NumPy
*  Pandas
*  MatPlotLib
*  Scikit-learn
*  Tensorflow/Keras

## Work Process Description

*  **Data Preprocessing**: the data was processed, NaN values were removed.
*  **Model Making**: the neural network with 3 linear layers was made with TensorFlow.
*  **Model Training**: the model had been trained on the train dataset.
*  **Metrics Calculating**: I got MSLE loss, MSE and MAE values as metrics of model training. MAE is the most representative metric in this case because of the task specificity – we want to minimize errors according to absolute difference between predicted and actual prices.
*  **Model Validation and Prediction**: model was tested by validation data and was used to predict the prices on test dataset.
