## Income-Classification

* **Predict whether a person makes over 50K a year or not given their demographic variation.** 


### Description

* To achieve this, several classification techniques are explored and the random forest model yields to the best prediction result.


### Install Setup

This project requires **Python 2.7** and the following Python libraries installed:

- [numpy](http://www.numpy.org/)
- [pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [seaborn](https://seaborn.pydata.org)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html)

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](http://continuum.io/downloads) distribution of Python, which already has the above packages and more included. Make sure that you select the Python 2.7 installer and not the Python 3.x installer.


### Code

Template code is provided in the notebook `Income_Classification.ipynb` 
[Jupyter Notebook](https://github.com/YRohitha/Income-Classification/blob/main/Income_Classification.ipynb) file.


### Run

In a terminal or command window, navigate to the top-level project directory (that contains this README) and run one of the following commands:

```bash
jupyter notebook Income_Classification.ipynb
```
or
```bash
ipython notebook Income_Classification.ipynb
```
This will open the Jupyter Notebook software and project file in your web browser.


### Data
#### The [income dataset](http://archive.ics.uci.edu/ml/machine-learning-databases/adult/adult.data) was extracted from 1994 U.S. Census database. 

### Features

#### 1. Categorical Attributes

* `workclass`: Individual work category
* `education`: Individual's highest education degree
* `marital-status`: Individual marital status
* `occupation`: Individual's occupation
* `relationship`: Individual's relation in a family
* `race`: Race of Individual
* `sex`
* `native-country`: Individual's native country


#### 2. Continuous Attributes

* `age`: Age of an individual
* `education-num`: Individual's year of receiving education
* `fnlwgt`: The weights on the CPS files are controlled to independent estimates of the civilian noninstitutional population of the US. These are prepared monthly for us by Population Division here at the Census Bureau.
* `capital-gain`
* `capital-loss`
* `hours-per-week`: Individual's working hour per week
