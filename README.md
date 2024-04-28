# Predicting Bike Sharing Patterns

This project builds a neural network to predict daily bike rental ridership using bike sharing data from the Capital Bikeshare system in Washington D.C.

## Data
The data comes from the Capital Bikeshare System Data and includes weather and seasonal information.

## Network Architecture

The network consists of:

- An input layer with number of input nodes equal to number of features
- A hidden layer with user-defined number of hidden nodes
- An output layer with one node for the predicted count
- ReLU activation for hidden layer
- No activation for output layer
- The network is trained for a defined number of iterations using stochastic gradient descent to minimize mean squared error loss.

## Usage

The main notebook is predicting_bike_sharing_data.ipynb. It will walk through the steps of:

1. Loading and preparing the data
2. Defining the network architecture
3. Training the network
4. Evaluating model performance

Key parameters to tweak for model optimization are number of hidden nodes and number of training iterations.
