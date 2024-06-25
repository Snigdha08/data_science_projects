# data_science_projects
Hosting a few interesting machine learning and data science projects here.

# California Housing Prices Prediction

## Introduction
This repository contains a machine learning project that predicts median house values in California districts based on census data from 1990. The project utilizes the California Housing dataset and implements a linear regression model.

## Dataset
The California Housing dataset includes the following features:
- MedInc: Median income in block group
- HouseAge: Median house age in block
- AveRooms: Average number of rooms per household
- AveBedrms: Average number of bedrooms per household
- Population: Block population
- AveOccup: Average house occupancy
- Latitude: Block latitude
- Longitude: Block longitude

The target variable is:
- MedHouseVal: Median house value for California districts

This dataset is a modified version of the California Housing dataset available from the StatLib repository.

## Model
The project uses a Linear Regression model to predict the median house values. The model was chosen for its simplicity and interpretability. The performance of the model is evaluated using the Mean Squared Error (MSE) metric.

## Installation
To set up the project environment to run the code, you will need Python and some packages which can be installed via pip. Here's how you can install the required packages:

```bash
pip install numpy pandas matplotlib scikit-learn seaborn
