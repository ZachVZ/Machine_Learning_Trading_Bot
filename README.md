# Machine_Learning_Trading_Bot

This notebook uses existing machine learning algorithm that will be adjusted to account for new data and evaluate how well the predictions line up with the actual outcomes.

Below are the actions that will be performed in this notebook.
1. Establish a Baseline Performance
2. Tune the Baseline Trading Algorithm
3. Evaluate a New Machine Learning Classifier
4. Create an Evaluation Report


## Technologies Require
* This project leverages python version 3.8.5
* pandas
* numpy
* pathlib
* hvplot
* matplotlib
* sklearn
* sklearn.preprocessing
* pandas.tseries.offsets
* sklearn.metrics
* Project will be accomplished in JupyterLab

## Installation Guide and Running Jupyter Notebook
Installing Jupyter notebook
* On the terminal (Git Bash) under the conda dev environment, type the code below:

pip install jupyterlab

* To open the Jupyter notebook
Open a new Git Bash and type the below command into your conda dev environment:

jupyter lab

* then hit the ENTER key to run


## Required Imports
* pandas - Data manipulation and analysis
* numpy - Support for large, multi-dimensional arrays and matrices, along with a large collection of high-level mathematical functions
* pathlib - Imports csv files
* hvplot - Interactive visualization
* matplotlib - Plotting libabry that provides an object-oriented API for embedding plots into applications
* sklearn svm- Uses a subset of training points in the decision function, its also memory efficient
* sklearn.preprocessing StandardScaler- Removes the mean and scales each feature/variable to unit variance
* pandas.tseries.offsets DateOffset - Standard kind of date increment used for a date range in Pandas.
* sklearn.metrics classification_report- Displays main classification metrics such as the accuracy score, precision, recall, and f1 score


## Install Guide
# Imports
* import pandas as pd
* import numpy as np
* from pathlib import Path
* import hvplot.pandas
* import matplotlib.pyplot as plt
* from sklearn import svm
* from sklearn.preprocessing import StandardScaler
* from pandas.tseries.offsets import DateOffset
* from sklearn.metrics import classification_report

## Usage
To use the notebook:
1. Clone the repo
2. Run jupter lab git bash
3. Open file machine_learning_trading_bot.ipynb


### Contributors
Zach Zwiener

### Contact
Email - zachzwiener3@gmail.com

### License
MIT
