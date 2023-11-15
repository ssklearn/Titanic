# Titanic Survival Prediction

This project predicts the survival of passengers on the Titanic.

## Overview

The goal of this project is to predict whether a passenger survived or not based on various features such as age, gender, class, and fare. The dataset used for this project is from the Kaggle Titanic competition.

## Data

The data files used in this project are:
- `train_titanic.csv`: Training data
- `test_titanic.csv`: Testing data

## Features

- `Pclass`: Passenger class (1st, 2nd, or 3rd)
- `Sex`: Gender of the passenger
- `Age`: Age of the passenger
- `SibSp`: Number of siblings/spouses aboard
- `Parch`: Number of parents/children aboard
- `Fare`: Fare paid by the passenger
- `Embarked`: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

## Preprocessing

- Combined "SibSp" and "Parch" into a new feature "FamilySize"
- Extracted titles from names and mapped them to numerical values
- Filled missing age values with the overall median age
- Filled missing fare values in the test data with the median fare

## Model

A random forest classifier is used to make predictions.

## Results

The model achieved a Kaggle competition score of 0.77990.

## How to Use

1. Clone the repository:

   ```bash
   git clone https://github.com/ssklearn/Titanic.git

1. Install the required libraries:
   pip install -r requirements.txt
2. Run the Jupyter Notebook:
   jupyter notebook titanic.ipynb

## License

This project is licensed under the MIT License
