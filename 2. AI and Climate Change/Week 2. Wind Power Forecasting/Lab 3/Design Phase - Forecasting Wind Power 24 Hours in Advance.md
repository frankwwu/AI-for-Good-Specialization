# Design Phase - Forecasting Wind Power 24 Hours in Advance

[__Launch Notebook!__](https://www.coursera.org/learn/ai-and-climate-change/ungradedLab/LB8AQ/design-phase-forecasting-wind-power-24-hours-in-advance/lab?path=%2Fnotebooks%2FC2_W2_Lab_3_Wind_Energy_Design_2.ipynb)

## Instructions

In previous labs you explored the data from your wind farm and confirmed that the features it included can be used to determine the power output at any given time with reasonable accuracy. But what about forecasting power output in the future?

In this lab you will compare different forecasting techniques to __predict the power output of one of the turbines of your wind farm for the next 24 hours__. Notice that this process can be replicated for all the turbines to predict the total power output of your wind farm. This lab uses the Tensorflow framework for making forecasts and draws inspiration from their [official guide](https://www.tensorflow.org/tutorials/structured_data/time_series) on time series forecasting, so go check it out if you are interested in understanding more about how the code works.

The steps you will take in this lab are:

1. Import Python packages

2. Load the dataset

3. Slice your data and resample to an hourly frequency

4. Split your data into train, validation, and test sets

5. Establish a baseline

6. Visualize a time series of your target and predictors

Train neural network models using historical data

Include wind speed forecasts in your model
