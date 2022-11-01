# MMA Bout Prediction

This repository contains a machine learning pipeline developed to predict the outcome of MMA bouts. Specifically, the data used was drawn from UFC bouts. 

The problem was framed as a binary classification problem, excluding bouts which ended in a draw. 

All models were trained using the sklearn library. Functionality from this library was heavily used in the data cleaning and preparation as well.

The best accuracy achieved with any of the classifiers trained was in the neighborhood of 70%. Full results including ROC curves and precision recall curves can be found in the project report and the final notebook.

I completed this as an independent project for the Machine Learning (CS 6140) course in Fall 2021 at Northeastern University while pursuing a master's degree in computer science.

## Project Structure

- `project_report_vfranz.pdf`: a final write up of the project and the results
- `mma_prediction.ipynb`: juptyer notebook containing the culmination of the work on the project including the final data preparation processing, model training process and the visualizations of the results
- `data_exploration.ipynb` and `data_exploration_v2.ipynb`: data exploration and scratch work done for data preparation and model training, v2 is more substantial and contains more of the work done for feature engineering

## Data Source

The data source for this project is the following Kaggle page: https://www.kaggle.com/datasets/rajeevw/ufcdata. Huge credit to the creator and maintainer of this dataset. 
