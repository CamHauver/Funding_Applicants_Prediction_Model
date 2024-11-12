# Funding_Applicants_Prediction_Model

This project involves creating a machine learning and neural networks to build a binary classifier that can predict applicant success if funded by the nonprofit organization, Alphabet Soup. Python, pandas, sklearn, TensorFlow, Keras, and Google Colab were utilized for this project.

Original code sources: Data Analytics course Module 21 Challenge files. Data Analytics course instructor, Andrew Hoang's, speed run Zoom recording for Module 21 Challenge.

Code for the model can be found in the Notebooks directory and in DataPreprocessCompileTrainModel.ipynb (for initial model) and ModelOptimization.ipynb (for optimized model)

See ReportNeuralNetworkModel.ipynb for analysis report and summary

See AlphabetSoupCharity.h5 for intial model
See OptimizedAlphabetSoupCharity.h5 for optimized model 

#Data source: https://static.bc-edx.com/data/dl-1-2/m21/lms/starter/charity_data.csv

1) Data was first preprocessed using Pandas DataFrames
2) Undesirable columns were dropped before assigning a target variable and features variables
3) Data was then narrowed down by grouping less significant categorical variables
4) Categorical variables were then encoded using get_dummies
5) Preprocessed data was then split into training and testing datasets
6) StandardScaler was used to fit the feature dataset and then it was fit to the training data using the transform function
7) Data was then compiled, and the neural network/deep learning model was trained and evaluated using TensorFlow and Keras in Google Colab
8) The number of neurons and layers in the model required for optimization were determined by the number of inputs and trial and error
9) To achieve desired accuracy of >75%, the model was optimized ny increasing the number of neurons and hidden layers, as well as introducing NAMES as a feature when it was previously dropped from the data
10) Both model versions were saved as HDF5 files

