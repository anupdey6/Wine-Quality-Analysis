# Wine Quality Analysis


<p align="center">
  <img width="500" height="300" src="https://raw.githubusercontent.com/anupdey6/Wine-Quality-Analysis/main/wine.jpg">
</p>



# Table of Contents
1. [Introduction](#Introduction)
2. [Data Description](#Data-Description)
3. [Specifications](#Specifications)
4. [Data Pre-processing](#Data-Pre-processing)
5. [Basic Exploratory Analysis](#Basic-Exploratory-Analysis)
6. [Modeling](#Modeling)
7. [End Note](#End-Note)






## Introduction

The purpose of this project is to conduct an analysis of Wine Quality data from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/wine+quality). The data are the results of a chemical analysis of wines grown in the same region in Italy but derived from three different cultivars. The data has 13 attributes which are wine type, fixed acidity, citric acid, residual sugar, chlorides, free sulfur dioxide, total sulfur dioxide, density, pH, sulphates, alcohol, and quality. We are interested to see if these attributes have an impact on the quality of the wine. The objective of this Exploratory data analysis of the Red wine dataset is to analyze the variables and determine which of the chemical properties of the wine influence its quality the most. Moreover, the final goal is to use machine learning to build an accurate model to predict wine quality.








## Data Description

The data contains 4547 observations with 12 features and 1 outcome
variable. Also, the data has two missing values in feature
total\_sulfur\_dioxide.

**Features** :

  - **wine type** - 1096 Red and 3451 White wine

  - **fixed acidity** - Most acids involved with wine or fixed or
    nonvolatile

  - **volatile acidity** - The amount of acetic acid in wine, which at
    too high of levels can lead to an unpleasant, vinegar taste

  - **citric acid** - the amount of acetic acid in wine, which at too
    high of levels can lead to an unpleasant, vinegar taste

  - **residual sugar** - The amount of sugar remaining after
    fermentation stops, it’s rare to find wines with less than 1
    gram/liter and wines with greater than 45 grams/liter are considered
    sweet

  - **chlorides** - The amount of salt in the wine

  - **free sulfur dioxide** - The free form of SO2 exists in equilibrium
    between molecular SO2 (as a dissolved gas) and bisulfite ion; it
    prevents microbial growth and the oxidation of the wine

  - **total sulfur dioxide** - Amount of free and bound forms of S02; in
    low concentrations, SO2 is mostly undetectable in wine, but at free
    SO2 concentrations over 50 ppm, SO2 becomes evident in the nose and
    taste of wine

  - **density** - The density of water is close to that of water
    depending on the percent alcohol and sugar content

  - **pH** - Describes how acidic or basic a wine is on a scale from 0
    (very acidic) to 14 (very basic); most wines are between 3-4 on the
    pH scale

  - **sulphates** - A wine additive that can contribute to sulfur
    dioxide gas (S02) levels, which acts as an antimicrobial and
    antioxidant

  - **alcohol** - The percent alcohol content of the wine

**Outcome Variable**:

  - **quality** - Score between 0 and 10


## Specifications 

The program used was Python 3.7.7 with the main packages used being [numpy](https://numpy.org), [pandas](https://pandas.pydata.org), [matplotlib](https://matplotlib.org/stable/index.html#), [seaborn](https://seaborn.pydata.org) and [scikit-learn](https://scikit-learn.org/stable/index.html); occasionally, collections, statsmodels, and nltk were also used.

## Data Pre-processing

The wine quality data set used here are was presented by [[Cortez et al., 2009]](https://www.sciencedirect.com/science/article/abs/pii/S0167923609001377?via%3Dihub). It was very well structured regarding the data types,Null values and duplicates. Processing the data was only for finding specific insights. 


## Basic Exploratory Analysis

## Modeling



## End Note:

Please follow the social media links of the author_

<!-- Please don't remove this: Grab your social icons from https://github.com/carlsednaoui/gitsocial -->

<!-- display the social media buttons in your README -->


[![alt text][1.1]][1]
[![alt text][2.1]][2]


<!-- links to social media icons -->
<!-- no need to change these -->

<!-- icons with padding -->


[1.1]: http://i.imgur.com/yCsTjba.png (google plus icon with padding)
[2.1]: http://i.imgur.com/0o48UoR.png (github icon with padding)

<!-- icons without padding -->


[1.2]: http://i.imgur.com/VlgBKQ9.png (google plus icon without padding)
[2.2]: http://i.imgur.com/9I6NRUm.png (github icon without padding)


<!-- links to your social media accounts -->
<!-- update these accordingly -->


[1]: https://myaccount.google.com/profile
[2]: https://github.com/Sheikh-Nabil

<!-- Please don't remove this: Grab your social icons from https://github.com/carlsednaoui/gitsocial -->

<a href="#top">Back to top</a>

<details>
<summary>Refferences</summary>
<pre>

https://www.javatpoint.com/machine-learning-decision-tree-classification-algorithm

https://www.tutorialspoint.com/machine_learning_with_python/classification_algorithms_logistic_regression.htm

https://towardsdatascience.com/machine-learning-basics-with-the-k-nearest-neighbors-algorithm-6a6e71d01761
