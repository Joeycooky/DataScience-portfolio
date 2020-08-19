# BMW price prediction 
This is a jupyter notebook that does exploratory data analysis, feature engineering and tries to predict BMW car price in UK market.
## Install
This project requires **Python 3.x** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [Seaborn](https://seaborn.pydata.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)

We recommend students install [Anaconda](https://www.continuum.io/downloads), a pre-packaged Python distribution that contains all of the necessary libraries and software for this project.

## Files
- `bmw price prediction.ipynb`: This is the main notebook to analyze the data using EDM to help inform the feature engineering process and then to seek to find the best supervise learning model that attains the highest accuracy on the testing set.
- `datasets_750216_1305559_bmw.csv`: The dataset used for study


## Run

In a terminal or command window, navigate to the top-level project directory that contains this README and run one of the following commands:

```bash
ipython notebook bmw price prediction.ipynb
```  
or
```bash
jupyter notebook bmw price prediction.ipynb
```

This will open the iPython Notebook software and project file in your browser.

## Data

The dataset has 10,781 entries, later we'll split it into training and test set.

The original features are:
- model : model of the cars (i.e. 5 Series, X3, etc.)
- year : year of 1st hand purchased
- transmission : mode of transmission (manual or automatic or semi-auto)
- mileage : total mileage of the car
- tax : road tax incured
- mpg : miles per gallon consumption
- engineSize : in units of litres

## Notes
This notebook is only for self-learning purpose
