# Starbucks Data Analysis
(Part of Udacity's Data Scientist Nanodegree using data from Starbucks) 
In this project, data from Starbucks is analysed to build a machine learning modul to predict the success rate of offers for customers.

The approach is described in a blog post, which can be found here:
https://mijka127.medium.com/starbucks-data-analysis-v2-d604195fe23b

In the project in dive into the provided datasets, clean them and create a single data set which is then used to train different machine learning models. Those models are then evaluated, tuned and validated via k-fold cross validation. However, the end result does not meet my expectations, because the quality of they predictions stays on a poor level even after optimization.

## Dependencies
The project is using Jupyther Notebook from the Anaconda distribution for Python3.
Additionally, the following Python libraries will be used:
- Pandas
- Numpy
- Mathplotlib
- sklearn
- math
- json

## Installing the project
1. Clone the project into your repository
git clone https://github.com/michka127/udacity-data_scientist-Starbucks_Data_Analysis.git
2. Unzip data.zip in the project folder.

## Running te project:
Open Starbucks_Capstone_notebook.ipynp using Jupyter Notebooks from the Anaconda distribution for Python3.
Run the notebook.

## Important folders and files
Starbucks_Capstone_notebook.ipynp: The Jupyther Notebook that does the analysis

plots: This folder contains all plots created during analysis

data.zip: This archive contains the data provided from Starbucks:
- portfolio.json, data about the offers
- profile.json, data about the customers
- transcript.json, data about events during the experiment

## Acknowledgements
The data used for the analysis was published by Starbucks.

This project is part of the Udacity's Data Scientist Nanodegree programm: https://www.udacity.com/course/data-scientist-nanodegree--nd025
