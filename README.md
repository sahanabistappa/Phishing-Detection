# Phishing-Detection
# Code Readme

This code is designed to perform classification using the Gradient Boosting Classifier algorithm. It utilizes a dataset consisting of features and corresponding labels for phishing detection. The code follows the steps below:

1. Importing necessary libraries: `numpy`, `pandas`, `matplotlib.pyplot`, `sklearn`, and `csv`.
2. Data preprocessing: Reading the training dataset (`Phising_Training_Dataset.csv`) into a pandas DataFrame (`df`) and extracting the features (`X`) and labels (`y`) from the DataFrame.
3. Reading the testing dataset (`Phising_Testing_Dataset.csv`) into another pandas DataFrame (`df2`) and extracting the features for testing (`x_test`).
4. Splitting the training data into training and testing sets using the `train_test_split` function from `sklearn.model_selection`.
5. Printing the length of the training set.
6. Evaluating Recursive Feature Elimination (RFE) for classification: Generating synthetic data using `make_classification` and applying RFE using a Decision Tree Classifier as the estimator.
7. Creating a pipeline for the RFE and classification model.
8. Fitting the pipeline to the synthetic data.
9. Predicting the labels for the test dataset (`x_test`) using the trained pipeline model.

Please note that you need to have the `Phising_Training_Dataset.csv` and `Phising_Testing_Dataset.csv` files in the same directory as this code file for it to run successfully.
