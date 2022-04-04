# ML-6070: CA-06

kNN based Recommender Engine

Project Description: 

In this project we utilize Python's Sklearn machine learning library, specifically, the kNN algorithm to identify relationships between the data. This program runs using data from UCI’s IMDB data set containing thirty movies, including data for each movie across seven genres and their IMDB ratings. With this program it identifies 5 movies in the dataset that are the most similiar to given parameters. In this case we use parameters specific to the film, "The Post" and it returns those moveis that are the most similar based on the kNN machine learning algorithm in Python.

How to Install and Run Project:

**This link and code below is crucial in running the program, as it used in the code**

url = "https://github.com/ArinB/CA05-kNN/raw/master/movies_recommendation_data.csv"
data = pd.read_csv(url, encoding = "ISO-8859-1") 

First, download CA-06 zip file from GitHub. Unzip folder on local drive, then open Google Colab. Upload AS-CA06.ipynb file in Colab. Once .ipynb file is open all cells will run without error. Ensure Python packages and functions listed below are installed:

- import matplotlib.pyplot as plt
- import pandas as pd
- import numpy as np
- from sklearn.neighbors import NearestNeighbors
- from sklearn.neighbors import KNeighborsClassifier

Author: Alena Sanchez
