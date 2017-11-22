# Tensorflow-Iris
This repository contains solutions to the [Tensorflow problem sheet](https://emerging-technologies.github.io/problems/tensorflow.html) completed as part of my course work for the module [Emerging Technologies](https://emerging-technologies.github.io/). The data set used for this problem sheet is [Fisher's Iris data set](https://en.wikipedia.org/wiki/Iris_flower_data_set). The module is taught to undergraduate students at [GMIT](http://www.gmit.ie/) in the Department of Computer Science and Applied Physics for the course [B.S.c. (Hons) in Software Developement.](https://www.gmit.ie/software-development/bachelor-science-honours-software-development) The lecturer is  [Dr. Ian McLoughlin](https://ianmcloughlin.github.io/).

## Fisher's Iris Data Set:
The Iris flower data set was introduced by the British statistician and biologist [Ronald Fisher](https://en.wikipedia.org/wiki/Ronald_Fisher) in 1936 as an example of [linear discriminant analysis](https://en.wikipedia.org/wiki/Linear_discriminant_analysis). The data set contains 50 samples from each of three species of Iris(Iris setosa, Iris virginica and Iris versicolor). Four features were measured from each sample: the length and the width of the sepals and petals in centimeters. Based on the combination of these four features, Fisher developed a linear discriminant model to distinguish the species from each other. Based on Fisher's linear discriminant model, this data set became a typical test case for many statistical classification techniques in machine learning such as [support vector machines](https://en.wikipedia.org/wiki/Support_vector_machine).

## How to run:
All of the code can be viewed inside `Tensorflow-Iris.ipynb` along with the results of running the code by clicking this **[link](https://github.com/RicardsGraudins/Tensorflow-Iris/blob/master/Tensorflow-Iris.ipynb)**.

If you would like to run the code **locally**, do the following:  
Download the repository and using the command console CD into the directory and launch jupyter notebook by typing `jupyter notebook` and in the browser window that pops up click on `Tensorflow-Iris.ipynb`. To run the code click inside the coding blocks and press shift enter, the code should be run starting from exercise 1 onwards, otherwise if the code is run starting from the exercise 3 coding block for example, an error will be displayed as certain variables, imports etc. will not have been defined without running all the other exercises first.

### Prerequisites:
When running the code locally the following prerequisites must be installed:  
* Python.  
  - Recommended version [3.6.1](https://www.python.org/downloads/release/python-361/).
* Jupyter.  
  - Installation guide available [here](http://jupyter.readthedocs.io/en/latest/install.html).
* Matplotlib.  
  - Installation guide available [here](https://matplotlib.org/downloads.html).
* Numpy.  
  - Installation guide available [here](http://www.numpy.org/).
* Seaborn.  
  - Installation guide available [here](https://seaborn.pydata.org/installing.html).
* Pandas.
  - Installation guide available [here](https://pandas.pydata.org/pandas-docs/stable/install.html).
* Tensorflow.
  - Installation guide available [here](https://www.tensorflow.org/install/).
  - Takes approx 5-10 minutes to install Tensorflow with CPU support.

**Alternatively** you can download [anaconda](https://anaconda.org/anaconda/python) which comes with **all** (excluding Tensorflow) of the above and other commonly used packages for scientific computing and data science. The Jupyter website has a quick guide on installing anaconda that is recommended for new users available [here](http://jupyter.readthedocs.io/en/latest/install.html). I recommended installing anaconda as it is a much faster and easier way to get this project up and running as fast as possible.


## Exercises: 
## 01. Use Tensorflow to create model
Use Tensorflow to create a model to predict the species of Iris from a flower’s sepal width, sepal length, petal width, and petal length. 
## 02. Split the data into training and testing 
Split the data set into a training set and a testing set. You should investigate the best way to do this, and list any online references used in your notebook. If you wish to, you can write some code to randomly separate the data on the fly.
## 03. Train the model 
Use the testing set to train your model.
## 04. Test the model
Use the testing set to test your model, clearly calculating and displaying the error rate.
