# LSTM
This is a LSTM  for Appliance Consumption Prediction

Time Series Prediction with LSTM Neural Networks
This dataset contains various features related to energy consumption in a residential building.

You can find the dataset here: https://archive.ics.uci.edu/dataset/374/appliances+energy+prediction 

Importing Libraries: I used Pandas for handling the data, NumPy for math operations, sklearn for data preparation, and TensorFlow Keras to create my LSTM model.

Loading and Understanding Data: I loaded the data with Pandas and explored it to get a good understanding of what it contains.

Preparing the Data:

Handling Missing Data: I checked for and addressed any missing values to ensure the quality of the data.
Normalizing Features: I applied MinMaxScaler to scale the features to a uniform range, making sure they're consistent for the neural network.
Scaling the Target Variable: Similarly, I scaled the target variable (like 'Appliances') to align it with the other data.
Setting Up Time Series Data:

Creating Sequences: Since LSTMs need data in sequence format, I converted the data into sequences to capture the time-related patterns.
Splitting the Data: I split the data into training and testing sets to train the model and then evaluate it.
Building the LSTM Model:

Sequential Model: I chose a straightforward, layer-by-layer model structure.
LSTM Layers: I added these layers to detect patterns in the sequence data.
Dense Layer: I used this for the model's output.
Adam Optimizer: I used this optimizer for its adaptive learning rate, making my model learn more efficiently.
Training the Model: I trained my model by setting the number of epochs and the batch size, which dictate how the model learns from the data.

Evaluating the Model: I tested the model on new, unseen data to check how well it can generalize its learning.

Making Predictions and Visualizing Them: Finally, I used my trained model to make predictions and then created plots to compare these predictions against the actual values, visually assessing how well my model performed.






