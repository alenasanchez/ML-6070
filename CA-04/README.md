# ML-6070: CA-04

Ensemble Models

Project Description: 

In this project we utilize Python's Sklearn machine learning library along with xgboost to run and compare various ensemble models. Specifically, utilize algorithms such as the RandomForestClassifier, the AdaBoostClassifier, the GradientBoostingClassifier, and the XGBClassifier algorithms to train and test different models. This program runs using data from the US Census Bureau containing binary income classifications based on 7 features (age, capital gain/loss, education, hours per week, marriage status and relationship, occupation, and race and sex). We split the initial dataset of 48,842 records into a training set with 32,561 records and use a test set with 16,281 records to test the various models. This program also runs basic performance measures on the various models such as accuracy and AUC, so that we can compare and find the best model.

How to Install and Run Project:

**This link and code below is crucial in running the program, as it used in the code**

url = "https://github.com/ArinB/MSBA-CA-Data/blob/main/CA03/census_data.csv?raw=true"
data = pd.read_csv(url, encoding = "ISO-8859-1") 

First, download CA-04 zip file from GitHub. Unzip folder on local drive, then open Google Colab. Upload AS_CA_04.ipynb file in Colab. Once .ipynb file is open all cells will run without error. Lastly, ensure Python packages and functions such as from IPython.core.display import Image, import matplotlib.pyplot as plt, import pandas as pd, import numpy as np, from sklearn import tree, from sklearn.datasets import load_iris, import graphviz, from sklearn.tree import DecisionTreeClassifier, from IPython.display import Image, from sklearn.tree import export_graphviz, import pydotplus, from io import StringIO, from sklearn import metrics, from sklearn.metrics import confusion_matrix, from sklearn.metrics import accuracy_score, from sklearn.metrics import recall_score, from sklearn.metrics import precision_score , from sklearn.metrics import f1_score, from sklearn.metrics import classification_report, from sklearn.metrics import roc_curve, from sklearn.metrics import roc_auc_score, import time are imported as they are used in the program.

Author: Alena Sanchez

