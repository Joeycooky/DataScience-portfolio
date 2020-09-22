# Google Travel Review Clustering : divide Google review user into cluster of similar interest for further work of building recommender system based on thier preference.



## Install
This project requires **Python 3.x** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [seaborn](https://seaborn.pydata.org/)

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)

We recommend students install [Anaconda](https://www.continuum.io/downloads), a pre-packaged Python distribution that contains all of the necessary libraries and software for this project.

## Introduction
I'm kind of people who love traveling. But sometimes I've problems like where should I visit? Are there somewhere interesting places matched with my lifestyle? Often I spent hours to search for interesting place to go out. Such a waste of time.

What if we can build a recommender system which can recommend you several interesting venue based on your preferences. With information from Google review, I'll try to divide Google review user into cluster of similar interest for further work of building recommender system based on thier preference.

Google review is a platform where customers give a rating (from 0-5 stars) and leave a comment to a specific places in google maps


 ## Finding
 
>![Clustering Result](https://github.com/Joeycooky/DataScience-portfolio/blob/master/Google%20Travel%20Review%20Clustering/Img/Clustering%20Result.png) 
>![Rating Distribution of each cluster](https://github.com/Joeycooky/DataScience-portfolio/blob/master/Google%20Travel%20Review%20Clustering/Img/Review%20rating%20of%20each%20cluster.png)

with existing information : google review user can be segment into 4 different cluster as follow

- Cluster#0 (Green) : User who prefer nature like beaches and park, And also love to go to museums and theatres
- Cluster#1 (Orange) : Fast food lover, pay attention to hotel and juice bar and also have art in thier heart
- Cluster#2 (Light Blue) : Activities finder, this type of user love to go to local service, spend thier time in zoo, shopping in mall, having dinner in fine restaurant and pubs/bars
- Cluster#3 (Pink) : From scatter plot, member of this cluster are not loosely spread, they might or might not share common interest. Although user in this group gave overall rating about 2 to all attraction, but compared to other 3 clusters, they seem to have more attention to dance clubs, swimming pools, gyms, bakeries, beauty and spas, cafes, view points, monuments and gardens than above 3 clusters. Therefore cluster#3 can be summarized as healthy and sightseeing lover.

With information of how different user group prefer different attraction. We can further use this information to build recommender system where we can recommend specific type of attractions to specific user to enhanced thier traveling experience and boost revenue for attraction point.


## You can find more detail in notebook [here](https://nbviewer.jupyter.org/github/Joeycooky/DataScience-portfolio/blob/master/Google%20Travel%20Review%20Clustering/Google-Travel-Review-Clustering.ipynb)
## Notes
This notebook for self-learning purpose only
