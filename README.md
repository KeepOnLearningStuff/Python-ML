# Project Description & Objectives
The aim of this project is to ensure book readers are comfortable enough with the recommenders so they can have easier time figuring out which book/books they want to read next.
The dataset that was used on this project is a curation of Goodreads books based on real user information.
Using the dataset, main objective is to train a model that predicts a book’s rating. The project will be represented as a Jupyter Notebook and includes exploratory analysis of the data, feature engineering and selection, model training and evaluation and finally, deployment.
  - Data analysis (data processing, data cleaning, exploratory analysis, plots of relevant attributes) and feature selection (feature engineering, feature pruning, choice
justification).
  - Model training (motivation for selected model, comparison of different models) and evaluation (evaluation metric, results interpretation).

# Prerequisites
  - https://jupyter.org/install
  - https://conda.io/projects/conda/en/latest/user-guide/install/index.html

Jupyter notebooks will be uploaded here for anyone that wishes to improve or try it out on their own.
As for Conda "conda env create -f goodreads-rating.yml" command will create the necessary environment

# Packages That Were Used
  - Numpy : It is a Python library that provides a multidimensional array object, various derived objects (such as masked arrays and matrices), and an assortment of routines for fast operations on arrays, including mathematical, logical, shape manipulation, sorting, selecting, I/O, discrete Fourier transforms, basic linear algebra, basic statistical operations, random simulation and much more.
  - Pandas : Pandas is an open source Python package that is most widely used for data science/data analysis and machine learning tasks. It is built on top of another package named Numpy, which provides support for multi-dimensional arrays.
  - Plotly : Plotly is an open-source data visualization library for Python and R written in JavaScript, making graphs inherently interactive. They can be modified tremendously and are easily exported as images, HTML, etc. for seamless integration into a number of applications.
  - Sklearn : Scikit-learn is a key library for the Python programming language that is typically used in machine learning projects. Scikit-learn is focused on machine learning tools including mathematical, statistical and general purpose algorithms that form the basis for many machine learning technologies.
  - ibmlearn : Imblearn library is specifically designed to deal with imbalanced datasets. It provides various methods like undersampling, oversampling, and SMOTE to handle and removing the imbalance from the dataset. This library consists of various ensemble methods like bagging classifiers, random forest and boosting classifiers that can be used to train models for imbalanced data sets with very efficient accuracy.
# Usage 
There will be 4 different approaches of the Project uploaded to this Repositories.
Using different ways to train the model with different predection rates.Algorithms that were used are:
  - Linear regression (in scikit-learn) is the most basic form, where the model is not penalized for its choice of weights, at all. That means, during the training stage, if the model feels like one particular feature is particularly important, the model may place a large weight to the feature. It can lead to overfitting.
  - Ridge regression penalizes the model for the sum of squared value of the weights. Thus, the weights not only tend to have smaller absolute values, but also really tend to penalize the extremes of the weights, resulting in a group of weights that are more evenly distributed.
  - Random Forest Regression algorithms are a class of Machine Learning algorithms that use the combination of multiple random decision trees each trained on a subset of data. The use of multiple trees gives stability to the algorithm and reduces variance. The random forest regression algorithm is a commonly used model due to its ability to work well for large and most kinds of data.
