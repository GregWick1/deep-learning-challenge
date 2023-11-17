# deep-learning-challenge
This is a repository for my module 21 deep learning challenge

Step 1: Preprocess the Data
  Using your knowledge of Pandas and scikit-learn’s StandardScaler(), you’ll need to preprocess the dataset. This step prepares you for Step 2, where you'll compile, train, and evaluate the neural network model.

  Start by uploading the starter file to Google Colab, then using the information we provided in the Challenge files, follow the instructions to complete the preprocessing steps.

  Read in the charity_data.csv to a Pandas DataFrame, and be sure to identify the following in your dataset:
    * What variable(s) are the target(s) for your model?
    *What variable(s) are the feature(s) for your model?
    *Drop the EIN and NAME columns.

  Determine the number of unique values for each column.

  For columns that have more than 10 unique values, determine the number of data points for each unique value.

  Use the number of data points for each unique value to pick a cutoff point to bin "rare" categorical variables together in a new value, Other, and then check if the binning was successful.

  Use pd.get_dummies() to encode categorical variables.

  Split the preprocessed data into a features array, X, and a target array, y. Use these arrays and the train_test_split function to split the data into training and testing datasets.
  
  Scale the training and testing features datasets by creating a StandardScaler instance, fitting it to the training data, then using the transform function.


Step 2: Compile, Train, and Evaluate the Model

  Continue using the file in Google Colab in which you performed the preprocessing steps from Step 1.

  Create a neural network model by assigning the number of input features and nodes for each layer using TensorFlow and Keras.

  Create the first hidden layer and choose an appropriate activation function.

  If necessary, add a second hidden layer with an appropriate activation function.

  Create an output layer with an appropriate activation function.

  Check the structure of the model.

  Compile and train the model.

  Create a callback that saves the model's weights every five epochs.

  Evaluate the model using the test data to determine the loss and accuracy.

  Save and export your results to an HDF5 file. Name the file AlphabetSoupCharity.h5.

Step 3: Optimize the Model

  Create a new Google Colab file and name it AlphabetSoupCharity_Optimization.ipynb.

  Import your dependencies and read in the charity_data.csv to a Pandas DataFrame.

  Preprocess the dataset as you did in Step 1. Be sure to adjust for any modifications that came out of optimizing the model.

  Design a neural network model, and be sure to adjust for modifications that will optimize the model to achieve higher than 75% accuracy.

  Save and export your results to an HDF5 file. Name the file AlphabetSoupCharity_Optimization.h5.
