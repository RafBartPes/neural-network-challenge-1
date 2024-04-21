# neural-network-challenge-1

## Neural Network Binary Classification Project ##
### Project Overview ###
This project utilizes a neural network to perform binary classification on a dataset concerning credit ranking. The goal is to predict the binary credit ranking based on various features provided in the dataset. The neural network is built using TensorFlow and Keras, trained with historical data, evaluated for accuracy, and its predictions are analyzed.

## Features ##
    Data loading from a CSV file
    Data preprocessing including scaling
    Neural network training and evaluation
    Saving and loading the model
    Making predictions and generating a classification report


## Prerequisites ##
To run this project, you need to have Python installed on your system along with the following Python libraries:    
    pandas
    sklearn
    TensorFlow
    Keras
    pathlib

## Code Description ##
    Data Loading: The script starts by loading the dataset from a specified URL into a pandas DataFrame.
    Preprocessing: The data is then preprocessed, where it is split into features (X) and the target variable (y). The features are scaled using StandardScaler.
    Model Training: A Sequential model is built and trained using the processed data.
    Model Evaluation: After training, the model is evaluated on a test set.
    Prediction: Predictions are made on the test set, converted to binary format, and a classification report is generated to evaluate performance.
    Model Saving: The trained model is saved to the local filesystem for future use.

## Output ##
The output includes:

Model summary
Training loss and accuracy
Evaluation results on test data
Sample predictions
A classification report providing detailed metrics
Contributions
Contributions to this project are welcome. Please fork the repository and submit a pull request with your enhancements.
