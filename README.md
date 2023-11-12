# Prediction of fashion labels using 'Fashion MNIST' dataset
Repository made for Data Science course at Cracow School of Business. It contains comparison of different data science predicting models. 

## The aim of the project
The aim of the project was to create a machine learning model which goal was to assign an image to a given category. The data used in the project comes from the Fashion MNIST data set.
To obtain the best results, several models were built based on:
- Logistic Regression
- Deep Neural Networks (DNN - Deep Neural Networks)
- Convolutional Neural Networks (CNN) 
## The data set 
The dataset - Fashion MNIST - used in this project comes from the fashion retailer Zalando. 
The fashion MNIST dataset consists of two parts - the first one is training part containing 60 000 samples, and the second one is a testing part containing 10 000 samples. 
Each sample is a black and white image with dimensions of 28 x 28 pixels, belonging to one of the 10 classes. 
The classes included in the dataset are: 
- T-shirt/top, 
- Trousers, 
- Pullover, 
- Dress, 
- Coat, 
- Sandal, 
- Shirt, 
- Sneaker, 
- Bag, 
- Ankle Boots.

## Results

The model that achieved the greatest effectiveness is the Convolutional Neural Network Model with an added dropout layer. 
This model has an accuracy of 86.7%.
![Convolutional Network Model with Dropout Accuracy](/data_visualization/conv_net_acc.png "Convolutional Network Model with Dropout Accuracy")

The model with the least effectiveness turned out to be the Logistic Regression Model, which achieved an R^2 value of 78.87% for training data and 75.83% for validation data.