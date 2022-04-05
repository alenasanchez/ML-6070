# ML-6070: CA-05

Logistic Regression

Project Description: 

In this project we utilize Python's Sklearn machine learning library, specifically, the Logistic Regression algorithm to develop a binary classifier model to predict CVD Risk. This program runs using CVD data containing the following vaiables:

- age_s1	
- race	
- educat	
- mstat	
- hip	
- neck20	
- waist	
- av_weight_kg	
- cgpkyr	
- tea15	
- srhype	
- parrptdiab	
- bend25	
- happy25	
- tired25	
- hlthlm25

These independent variables affect the dependent variable (CVD_4types) which determines whether or not the subject is at risk of CVD. Additionally, in this program we run feature engineering and determine the features that have the most influence on CVD risk. Lastly, this program runs various performance metrics and displays an ROC curve to meausre the final model's performance.

How to Install and Run Project:

**This link and code below is crucial in running the program, as it used in the code**

url = "https://github.com/ArinB/CA05-B-Logistic-Regression/raw/master/cvd_data.csv"
data = pd.read_csv(url, encoding = "ISO-8859-1") 

First, download CA-05 zip file from GitHub. Unzip folder on local drive, then open Google Colab. Upload AS_CA05.ipynb file in Colab. Once .ipynb file is open all cells will run without error. Ensure Python packages and functions listed below are installed:

- import matplotlib.pyplot as plt
- import pandas as pd
- import numpy as np


Author: Alena Sanchez

