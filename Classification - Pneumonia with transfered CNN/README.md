# Pneumania Classification : Transfered CNN

I used this notebook personally to learn about Convolutional Neural Network and transfered learning. This notebook basicly used pretrained VGG16 model without top layer and train only newly created top layer by X-rays image of 1-5 years old children with labeled class.

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

![Pneumonia](https://github.com/Joeycooky/DataScience-portfolio/blob/master/Classification%20-%20Pneumonia%20with%20transfered%20CNN/Image/Lobar_pneumonia_illustrated.jpg)

Pneumonia is an inflammatory condition of the lung primarily affecting the small air sacs known as alveoli. Symptoms typically include some combination of productive or dry cough, chest pain, fever and difficulty breathing. The severity of the condition is variable. Pneumonia is usually caused by infection with viruses or bacteria, and less commonly by other microorganisms. Identifying the responsible pathogen can be difficult. Diagnosis is often based on symptoms and physical examination. Chest X-rays, blood tests, and culture of the sputum may help confirm the diagnosis. The disease may be classified by where it was acquired, such as community- or hospital-acquired or healthcare-associated pneumonia

 ## Preliminary Finding
 
![Result](https://github.com/Joeycooky/DataScience-portfolio/blob/master/Classification%20-%20Pneumonia%20with%20transfered%20CNN/Image/__results___16_0.png)

* Chest x-rays for people who are healthy (NORMAL) are clearer, minimal white shaded in lung area
* On the other hand, for people who have Pneumonia, their x-rays image seem more opaque.
## Result
![CM](https://github.com/Joeycooky/DataScience-portfolio/blob/master/Classification%20-%20Pneumonia%20with%20transfered%20CNN/Image/CM.png)
![ROC](https://github.com/Joeycooky/DataScience-portfolio/blob/master/Classification%20-%20Pneumonia%20with%20transfered%20CNN/Image/result.png)

## Conclusion
With limited time, we're able to build x-rays image classifier to classify to correctly predict Pneumonia chest x-rays with minimal Pneumonia cases wrongly classify as Normal (FN). Then we try to improve model performance by fine tuning with class weight and few techniques. We have acheive some improvement, but our model still have high amount of false positive (Normal case wrongly classify as Pneumonia)

We can see that our accuracy on test set is about 92% (relatively lower than accuracy in training and validation set). This indicate significant level of overfitting. Try reduce model complexity by cutting off some layers of VGG16 and adjust regularization parameters such as drop out rate and L2 regularization in Dense layers may help.

Our recall is greater than our precision, which mean that almost all pneumonia x-ray images are correctly classified (which is our main objective) but there are some normal images wrongly identified. I will study further on how to solve this problem.



## You can find more detail in notebook [here](https://nbviewer.jupyter.org/github/Joeycooky/DataScience-portfolio/blob/master/Classification%20-%20Pneumonia%20with%20transfered%20CNN/pneumania-classification-transfered-cnn.ipynb)
## Notes
This notebook for self-learning purpose only
