## Overview

Built a model in Python to classify a mushroom as being poisonous or edible by looking at 23 features and 8124 examples. The
model was able to classify the mushrooms in the validation set (containing 3250 examples) with an accuracy greater than 99%.

## Brief Summary
This program has been created to look at data (which is in a csv format) and based on that make predictions as to whether a mushroom is poisonous or not. The dataset has been taken from kaggle. This is the link for the dataset: Mushroom Classification | Kaggle (safe to eat or deadly poison). The following are the main components of this program:

- Importing the required libraries
- Gettintg the directory of the data (CSV file)
- About the data
- Converting the data from a CSV format to a Pandas DataFrame
- Visualising some features of the data using a graph
- Converting categorial values into dummy variables
- Splitting the data into X and y
- Converting the Pandas DataFrame into a numpy array
- Checking if X and y have the appropriate dimensions
- Splitting X and y into X_train, X_test, y_train, y_test
- Checking the dimensions of X_train, y_train, X_test, y_test
- Creating a Sequential model
- Viewing the model's summary
- Visualising the layers in the model
- Compiling the model
- Adding EarlyStopping
- Visualising loss and binary accuracy
