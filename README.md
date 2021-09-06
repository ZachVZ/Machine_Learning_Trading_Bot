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



#### Tune the Baseline Trading Algorithm
1. Tune the training algorithm by adjusting the size of the training dataset. To do so, slice your data into different periods. Rerun the notebook with the updated parameters, and record the results in your `README.md` file. Answer the following question: What impact resulted from increasing or decreasing the training window?

2. Tune the trading algorithm by adjusting the SMA input features. Adjust one or both of the windows for the algorithm. Rerun the notebook with the updated parameters, and record the results in your `README.md` file. Answer the following question: What impact resulted from increasing or decreasing either or both of the SMA windows?
3. Choose the set of parameters that best improved the trading algorithm returns. Save a PNG image of the cumulative product of the actual returns vs. the strategy returns, and document your conclusion in your `README.md` file.



#### Evaluate a New Machine Learning Classifier
3. Backtest the new model to evaluate its performance. Save a PNG image of the cumulative product of the actual returns vs. the strategy returns for this updated trading algorithm, and write your conclusions in your `README.md` file. Answer the following questions: Did this new model perform better or worse than the provided baseline model? Did this new model perform better or worse than your tuned trading algorithm?





#### Create an Evaluation Report
In the previous sections, you updated your `README.md` file with your conclusions. To accomplish this section, you need to add a summary evaluation report at the end of the `README.md` file. For this report, express your final conclusions and analysis. Support your findings by using the PNG images that you created.


Step 1: Tune the training algorithm by adjusting the size of the training dataset.¶
To do so, slice your data into different periods. Rerun the notebook with the updated parameters, and record the results in your README.md file.

Answer the following question: What impact resulted from increasing or decreasing the training window?

Step 2: Tune the trading algorithm by adjusting the SMA input features.
Adjust one or both of the windows for the algorithm. Rerun the notebook with the updated parameters, and record the results in your README.md file.

Answer the following question: What impact resulted from increasing or decreasing either or both of the SMA windows?

Step 3: Choose the set of parameters that best improved the trading algorithm returns.¶
Save a PNG image of the cumulative product of the actual returns vs. the strategy returns, and document your conclusion in your README.md file.


Step 3: Backtest the new model to evaluate its performance.
Save a PNG image of the cumulative product of the actual returns vs. the strategy returns for this updated trading algorithm, and write your conclusions in your README.md file.

Answer the following questions: Did this new model perform better or worse than the provided baseline model? Did this new model perform better or worse than your tuned trading algorithm?


### Contributors
Zach Zwiener

### Contact
Email - zachzwiener3@gmail.com

### License
MIT