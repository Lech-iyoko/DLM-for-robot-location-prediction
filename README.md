# DLM-for-robot-location-prediction

## A single neuron neural network for Time series prediction of robot's location

A Time series task, using the past positions of a robots location to predict its future location

* Load the dataset from a text file containing robot position data over time.

* Visualize the robot's movement data using matplotlib to understand its patterns.

* Preprocess the data:
  - Normalize the sequence using MinMaxScaler for better model performance.
  - Split the sequence into samples where a series of 5 steps predicts the next step.

* Develop a neural network model using Keras:
  - Utilize a single-neuron layer architecture with a dropout layer to prevent overfitting.
  - Compile the model with the Adam optimizer, using Mean Squared Error (MSE) and Mean Absolute Error (MAE) as metrics.
  - Train the model with early stopping to prevent overfitting and optimize training performance.

* Evaluate the model:
  - Achieved a Train RMSE and MAE score to demonstrate model accuracy.
  - Evaluated the model’s performance on test data for validation.

* Visualize the results:
  - Plot actual versus predicted robot positions to compare model predictions against real data.
