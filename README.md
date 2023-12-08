# Google-Data-Analytics-Capstone
Repo for final project in Google Data Analytics Certificate

This project involved analysing and cleaning 14 GB of historic flight data from US airports and building a classification model to predict whether flights would be cancelled in US airports.

## Data Source

The data used for this project comes from [Kaggle](https://www.kaggle.com/datasets/tylerx/flights-and-airports-data).

## Project Environment
This project was done using the AWS ecosystem, utilising AWS's S3 bucket to store the data, and AWS's EMR to wranggle the data through a Jupyter Notebook interface. 

## Data Cleaning and Modelling
The PySpark library was used for data cleaning and model building due to its efficiency in handling large datasets. In addition, libraries such as matplotlib and seborn were used for visualisation. 

The model selected for this project was a Gradient Boosting Machine, which managed to achieve an AUC score of 87%.
