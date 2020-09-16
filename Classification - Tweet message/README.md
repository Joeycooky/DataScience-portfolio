# Wait a minute, Is this for real? : NLP with tweets 

This jupyter notebook will guide you through exploratory data analysis, feature engineering and building machine learning model to predict whether a given booking will be canceled or not?

## Install
This project requires **Python 3.x** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [seaborn](https://seaborn.pydata.org/)
- [tensorflow](https://www.tensorflow.org/)

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)

We recommend install [Anaconda](https://www.continuum.io/downloads), a pre-packaged Python distribution that contains all of the necessary libraries and software for this project.

## Introduction
Twitter has become an important communication channel in times of emergency. The ubiquitousness of smartphones enables people to announce an emergency they’re observing in real-time. Because of this, more agencies are interested in programatically monitoring Twitter (i.e. disaster relief organizations and news agencies).

But, it’s not always clear whether a person’s words are actually announcing a disaster. Take this example:

The author explicitly uses the word “ABLAZE” but means it metaphorically. This is clear to a human right away, especially with the visual aid. But it’s less clear to a machine.

So, we'll build a deep neural network with combination of Convolutional layers and LSTM layers to let its learn from labeled tweet.

 ## Preliminary Finding
 
>![EDA](https://github.com/Joeycooky/DataScience-portfolio/blob/master/Classification%20-%20Tweet%20message/EDA.png) 

* In training set, we've comparative amount of Real and Fake news. There should not be any problem with class imbalance
* In aspect of tweet message length, there is no significant different between real and fake disaster. Both of them median around 135 charaters
* For number of words per tweet, for average both real and fake disaster tweet has around 10-20 words per tweets. However, there is no significant different for distribution of each group

Therefore, I'll let's our model learn from it and let's see how they performed.

## Conclusion

So far we've developed a model to classify whether a tweeted tweet will be real disaster or not. With existing progress we are able to reach 83% accuracy on test set which is quite good. However I can identify some room for improvement as follow...

* try removing some uninterpretable phrases/words likes \x89ÛÓ or \x89Û_
* try different network architecture
* try different pretrained weight from GloVe variances

## You can find more detail in notebook [here](https://nbviewer.jupyter.org/github/Joeycooky/DataScience-portfolio/blob/master/Classification%20-%20Tweet%20message/wait-a-minute-is-this-for-real-nlp-with-tweets.ipynb)
## Notes
This notebook for self-learning purpose only
