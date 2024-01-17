# LSTM
This is a LSTM  for Appliance Consumption Prediction

Time Series Prediction with LSTM Neural Networks

Libraries Import
Pandas: 
-used for data manipulation and analysis. 
-offers data structures like DataFrames
NumPy: 
-Provides support for large, multi-dimensional arrays and matrices, along with a collection of mathematical functions to operate on these arrays.
MinMaxScaler (sklearn.preprocessing): 
-This tool scales features to (0, 1). 
-ensures that all input features have similar scales
train_test_split (from sklearn.model_selection):
-split data into training and testing sets
TensorFlow and Keras: TensorFlow is an open-source machine learning library. Keras is integrated into TensorFlow.
Data Loading and Initial Exploration
I first used Pandas to load and initially explore the data. Using Pandas provides an understanding of the dataset's structure and types of data a dataset contains.

Data Preprocessing for Machine Learning
Checking for Missing Values: Identifying and addressing missing values.
Normalizing Features with MinMaxScaler: Normalization standardizes the range of independent variables or features of data.
Scaling the Target Variable
Scaling the target variable ('Appliances') This ensures that the target variable is within the same scale as the input features.
