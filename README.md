# Parkinson-Disease-Prediction
Using machine learning to predict whether a person suffers from Parkinson’s disease or not

Overview
Parkinson's disease is a progressive nervous system disorder that affects movement. Symptoms of Parkinson's disease can be subtle and may include stiffness, tremors, and slowing of movement. Due to the lack of definitive diagnostic methods, early detection can be challenging. However, machine learning offers a promising approach to predicting whether a person has Parkinson's disease based on available data.

In this project, we use Python and various machine learning techniques to predict Parkinson's disease, utilizing a dataset that includes relevant features. The project demonstrates how data preprocessing, model training, and evaluation can be effectively managed using popular Python libraries.

Project Structure
Importing Libraries and Dataset:

Load and preprocess the dataset using Python libraries.
Essential libraries include Pandas, Numpy, Matplotlib, Seaborn, Sklearn, XGBoost, and Imblearn.
Libraries Used:

Pandas: To load and manipulate data in a 2D array format, making analysis tasks simpler.
Numpy: For fast array computations and efficient handling of large datasets.
Matplotlib/Seaborn: For data visualization to better understand the data distribution and relationships between variables.
Sklearn: A comprehensive library offering tools for data preprocessing, model training, and evaluation.
XGBoost: An advanced machine learning algorithm known for its high accuracy in prediction tasks.
Imblearn: Contains functions to address class imbalance issues, which is crucial for improving model performance.
Steps:

Data Loading: Load the dataset into a Pandas DataFrame.
Data Preprocessing: Clean the data, handle missing values, and perform any necessary transformations.
Feature Engineering: Select and engineer features that will be used in the machine learning models.
Model Development: Train multiple machine learning models, including Logistic Regression, SVM, and XGBoost.
Evaluation: Evaluate model performance using metrics like ROC-AUC, Confusion Matrix, and others.
Visualization:

Use Matplotlib and Seaborn for visualizing the data distribution, feature importance, and model performance.
Handling Data Imbalance:

Use the RandomOverSampler from the Imblearn library to address class imbalance, ensuring the minority class is adequately represented in the training set.
Getting Started
Prerequisites
Python 3.x
Required Python libraries: Pandas, Numpy, Matplotlib, Seaborn, Sklearn, XGBoost, Imblearn
