# HW-2_mesutYildiz_2200357098

# Banknote Authentication with Decision Tree

Project involves the use of a decision tree classifier to determine whether a banknote is real or fake based on features such as variance, skewness, kurtosis, and entropy. The data is from the UCI Machine Learning Repository.

# Requirements
The goal of this project is to:

Load and prepare the Banknote Authentication dataset.
Train a decision tree classifier to predict banknotes as real or fake based on features extracted.
Evaluate the performance of the model using metrics like accuracy, precision, recall, and F1-score.
Visualize the decision tree and check feature importance.
# Dataset

There are 1372 data points with the following features:

- variance: The variance of the image.
- skewness: The skewness of the image.
- curtosis: The kurtosis of the image.
- entropy: The entropy of the image.
- class: Target feature (0: Fake, 1: Authentic).

The dataset can be downloaded from UCI Repository - Banknote Authentication.

# Requirements

- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- scipy
- scikit-image

# Instructions to Run

Download the banknote authentication dataset from the UCI repository and extract it.
Place the dataset file (data_banknote_authentication.txt) in the project directory.
Open the project in a Python environment or Jupyter Notebook.
Load the dataset, train the decision tree model, and evaluate the performance.
Results:
The model's performance metrics (accuracy, precision, recall, F1-score) will be printed.
The decision tree will be visualized, and a confusion matrix will be displayed.
Feature importance will be plotted for interpretation.
# Structure

- decision_tree_banknote.py: Python script to load the data, train the model, and evaluate results.
- requirements.txt: File listing necessary Python packages.
- README.md: This file.
