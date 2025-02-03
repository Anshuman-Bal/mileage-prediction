# Car Mileage Prediction

This repository contains two Jupyter notebooks demonstrating two approaches for predicting car mileage (MPG) based on various features of the car. The two models used are **Simple Linear Regression** and **Multiple Linear Regression**.

## Overview

In this project, we explore and implement two different regression techniques to predict the miles per gallon (MPG) of a car based on various car attributes. The project leverages the `CarData.csv` dataset, which includes information about the car's weight, horsepower, model year, cylinders, and more.

- **Simple Linear Regression**: This approach uses only one feature (weight) to predict the MPG.
- **Multiple Linear Regression**: This approach uses multiple features, such as weight, horsepower, and other variables to predict MPG.

## Dataset

The dataset used in this project is the `CarData.csv` file, which contains the following columns:

- `mpg`: Miles per gallon (dependent variable)
- `cylinders`: Number of cylinders in the car engine
- `displacement`: Engine displacement
- `horsepower`: Engine horsepower
- `weight`: Weight of the car
- `acceleration`: Car's acceleration
- `model_year`: Year of the car's model
- `origin`: Country of origin
- `name`: Car name

## Requirements

Before running the notebooks, ensure that you have the following Python libraries installed:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
