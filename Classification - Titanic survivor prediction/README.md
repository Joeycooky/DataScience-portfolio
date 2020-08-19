# Titanic Survivor Prediction : 
as a part of Titanic: Machine Learning from Disaster competition (https://www.kaggle.com/c/titanic)

This jupyter notebook performs exploratory data analysis, feature engineering and predict whether the passengers in the test set are likely to survive the disaster or not?

## Install
This project requires **Python 3.x** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [seaborn](https://seaborn.pydata.org/)

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)

We recommend students install [Anaconda](https://www.continuum.io/downloads), a pre-packaged Python distribution that contains all of the necessary libraries and software for this project.

## Files
- `titanic survivor prediction.ipynb`: This is the main notebook to analyze the data and then to seek to find the best supervise learning model that attains the highest accuracy on the test set.
- `train.csv`: The labeled training dataset
- `test.csv`: The un-labeled testing dataset

## Run

In a terminal or command window, navigate to the top-level project directory that contains this README and run one of the following commands:

```bash
ipython notebook titanic survivor prediction.ipynb
```  
or
```bash
jupyter notebook titanic survivor prediction.ipynb
```

This will open the iPython Notebook software and project file in your browser.

## Data
Dataset is provided by Kaggle as a part of "Titanic: Machine Learning from Disaster" competition. The goal of this model is to predict whether given passenger will survive the disaster or not based on following features.

- Train set shape = 891 Rows, 12 Columns
- Test set shape = 418 Rows, 11 Columns

The original features are:
- Survival : 0 = No, 1 = Yes
- name : Passenger name including prefix
- pclass : A proxy for socio-economic status (SES) 1 = 1st, 2 = 2nd, 3 = 3rd
- Sex : Male / Female
- Age : Age in years (Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5)
- sibsp : # of siblings / spouses aboard the Titanic
- parch : # of parents / children aboard the Titanic
- ticket : Ticket number
- fare : Passenger fare
- cabin : Cabin number
- embarked : Port of Embarkation C = Cherbourg, Q = Queenstown, S = Southampton

## Notes
This notebook for self-learning and participated in "Titanic: Machine Learning from Disaster" competition
