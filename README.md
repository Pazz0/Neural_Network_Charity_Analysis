# Neural_Network_Charity_Analysis

Binary classifier capable of predicting whether applicants will be successful if funded

## Overview of the Analysis
The purpose of this analysis is to create and optimize a neural network model that can predict whether an Alphabet Soup-funded organization will be successful based on the features in the provided dataset.

## Results
### Data Preprocessing
The target variable for the model is IS_SUCCESSFUL.
The feature variables for the model include all columns except EIN, NAME, and the target variable IS_SUCCESSFUL.

The EIN and NAME columns are neither targets nor features and have been removed from the input data.
Compiling, Training, and Evaluating the Model
The neural network model consists of two hidden layers and an output layer. The first hidden layer has 80 neurons, and the second hidden layer has 30 neurons. The activation function used in both hidden layers is ReLU (Rectified Linear Activation), while the output layer uses the Sigmoid activation function.

The model's accuracy did not achieve the target performance of 75%. However, multiple optimization attempts were made to improve the model's performance.
The steps taken to increase the model's performance include:
* Removing noisy variables from features.
* Added more neurons to the hidden layers in different orders
* Adding additional hidden layers
* Changing the activation functions of the hidden and output layers. Sigmoid worked bets in this instance
* Some of the result notes are commented out

Summary
The deep learning model's overall results were not sufficient to reach the target accuracy of 75% despite multiple optimization attempts. For this classification, an alternative would be to use a different more simple model, such as a Random Forest Classifier or Gradient Boosting Classifier. These models can provide better classification results by combining multiple decision trees and considering different subsets of the dataset during the learning process. Additionally, further feature engineering and selection could also help improve the performance of the models.
