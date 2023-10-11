Sales Forecasting
=================

![alt text](viz/header.gif "gif")

Description
-----------------
Forecasting sales for 2022 based on five years of data, using machine learning.


Installation
---------------

`> pip install -r requirements.txt`

Next you need to fetch the train and test data from [kaggle](https://kaggle.com/competitions/playground-series-s3e19) and place at the directory `./data`. Run the script `./notebooks/model.ipynb` to train a model and to save predictions. This is needed for the reporting web app to run.

Usage
-----------------
Web application built with [streamlit.io](https://streamlit.io/):

`> streamlit run viz/app.py`

The notebook for data exploration and model building can be found in `./notebooks`


Credit
---------
Data was provided by [kaggle](https://kaggle.com/competitions/playground-series-s3e19).