# Titanic Survival Prediction

This project involves predicting whether a passenger survived the sinking of the Titanic or not. Two datasets are provided: `train.csv` contains information about a subset of passengers (891 in total) along with their survival status, while `test.csv` contains similar information without the survival status.

## Dataset Description

- `train.csv`: This dataset includes details of passengers and their survival status, serving as the "ground truth".
- `test.csv`: This dataset includes similar passenger information, but without the survival status. The goal is to predict the survival outcomes for these passengers.

## Data Dictionary

Variable | Definition | Key
--- | --- | ---
survival | Survival | 0 = No, 1 = Yes
pclass | Ticket class | 1 = 1st, 2 = 2nd, 3 = 3rd
sex | Sex | 
Age | Age in years | 
sibsp | # of siblings / spouses aboard the Titanic | 
parch | # of parents / children aboard the Titanic | 
ticket | Ticket number | 
fare | Passenger fare | 
cabin | Cabin number | 
embarked | Port of Embarkation | C = Cherbourg, Q = Queenstown, S = Southampton

Your task is to predict if a passenger survived the sinking of the Titanic or not. For each passenger in the test set, you must predict a 0 or 1 value for the variable.

Your score is the percentage of passengers you correctly predict. This is known as accuracy.


i did add more to the Model

ffdf