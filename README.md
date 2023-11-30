# Tensorflow Introduction
Jupyter Notebooks showcasing the fundamentals of TensorFlow and Neural Networks

* Python
  > * Programming language to run all frameworks
* TensorFlow
  > * Our Deep Learning framework of choice for this course
  > 
  > * Data as Tensors are passed to our models 
* Keras
  > * API to build our neural networks models
  > 
  > * Create Dense hidden layers with various number of hidden units
  > 
  > * Mean Absolute Error and Mean Squared Error loss functions
  > 
  > * Stochastic Gradient Descent (SGD) and Adam model optimizers
  > 
  > * Fit the models to our training data
  > 
  > * Model evaluation on Mean Absolute Error and Mean Squared Error
  > 
  > * EarlyStopping callbacks
  > 
  > * Saving and Laoding models (SavedModel, HDF5, and keras formats)
* NumPy
  > * Initialize scalars into Numpy array
  > 
  > * Convert tensors to NumPy arrays when necessary for computation
  > 
  > * Backend for Pandas DataFrame
  >
  > * `meshgrid` to plot decision boundaries created by a model predicting on X
* MatplotLib
  > * Scatter plots to visualize train, test and pred values
  > 
  > * Plotting a loss curve to analyze the effectivness of our models learning
  > 
  > * Plotting distribution of data pre-normalization
  >
  > * `contourf` and `scatter` to create a `plot_decision_boundary()` function 
* Pandas
  > * DataFrames - Import CSV data into a NumPy array
  > 
  > * `get_dummies` - One-hot encode a Pandas DataFrame
* scikit-learn
  > * `train_test_split` - separate our data set into training data and testing data
  > 
  > * `MinMaxScaler` - Normalize numerical columns in our dataset between 0-1
  > 
  > * `OneHotEncoder` - one-hot encode non-numerical columns in our dataset
  >
  > * `make_circles` - Create a large dataset of circles
