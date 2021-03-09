# Wine Quality Analysis


<p align="center">
  <img width="500" height="300" src="https://raw.githubusercontent.com/CodeAcademyBerlin/Data-Science/master/Module%201/images/wine.jpg?token=ARTHZ3C3NLLX62IKXVZ5SWTAI3PVY">
</p>



# Table of Contents
1. [Introduction](#Introduction)
2. [Used Tools](Used-Tools)
3. [Data Description](#Data-Description)
4. [Data Processing](#Data-Processing)
5. [Machine Learning](#Basic-Exploratory-Analysis)
6. [End Note](#End-Note)






## Introduction:

The purpose of this project is to conduct an analysis on Wine Quality data from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/wine+quality). The data are the results of a chemical analysis of wines grown in the same region in Italy, but derived from three different cultivars. The data has 13 attributes which are wine type, fixed acidity, citric acid, residual sugar, chlorides, free sulfur dioxide, total sulfur dioxide, density, pH, sulphates, alcohol, and quality. We are interested to see if these attributes has an impact on the quality of wine. The objective of this Exploratory data analysis of the Red wine dataset is to analyze the variables and determine which of the chemical properties of the wine influence its quality the most. Moreover, the final goal is to use machine learning to build an accurate model to predict the wine quality.








## Data Description: 

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
    prevents microbial growth and the oxidation of wine

  - **total sulfur dioxide** - Amount of free and bound forms of S02; in
    low concentrations, SO2 is mostly undetectable in wine, but at free
    SO2 concentrations over 50 ppm, SO2 becomes evident in the nose and
    taste of wine

  - **density** - the density of water is close to that of water
    depending on the percent alcohol and sugar content

  - **pH** - Describes how acidic or basic a wine is on a scale from 0
    (very acidic) to 14 (very basic); most wines are between 3-4 on the
    pH scale

  - **sulphates** - a wine additive which can contribute to sulfur
    dioxide gas (S02) levels, wich acts as an antimicrobial and
    antioxidant

  - **alcohol** - the percent alcohol content of the wine

**Outcome Variable**:

  - **quality** - score between 0 and 10




## Data Processing:

The wine quality data set used here are was presented by [[Cortez et al., 2009]](https://www.sciencedirect.com/science/article/abs/pii/S0167923609001377?via%3Dihub). It was very well structured regarding the data types,Null values and duplicates. Processing the data was only for finding specific insights. 


## Machine Learning: 


[Decision Tree](https://scikit-learn.org/stable/modules/tree.html): 

From a high level, decision tree induction goes through 4 main steps to build the tree:

1) Begin with  training dataset, which should have some feature variables and classification or regression output.

2) Determine the “best feature” in the dataset to split the data on; more on how we define “best feature” later.
 
3) Split the data into subsets that contain the possible values for this best feature. This splitting basically defines a node on the tree i.e each node is a splitting point based on a certain feature from our data. 
 
4) Recursively generate new tree nodes by using the subset of data created from step 3. We keep splitting until we reach a point where we have optimised, by some measure, maximum accuracy while minimising the number of splits / nodes.


<p align="center">
  <img width="500" height="300" src="https://static.javatpoint.com/tutorial/machine-learning/images/decision-tree-classification-algorithm.png">
</p>




[K Nearest Neighbour](https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsClassifier.html):

The KNN Algorithm

1) Load the data
2) Initialize K to your chosen number of neighbors
3) For each example in the data, Calculate the distance between the query example and the current example from the data.
Add the distance and the index of the example to an ordered collection

4) Sort the ordered collection of distances and indices from smallest to largest (in ascending order) by the distances
5) Pick the first K entries from the sorted collection
6) Get the labels of the selected K entries
7) If regression, return the mean of the K labels
8) If classification, return the mode of the K labels

<p align="center">
  <img width="500" height="300" src="https://miro.medium.com/max/650/1*OyYyr9qY-w8RkaRh2TKo0w.png">
</p>

[Logistic Regression](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html):

Logistic regression is a supervised learning classification algorithm used to predict the probability of a target variable.The nature of target or dependent variable is dichotomous, which means there would be only two possible classes.

Generally, logistic regression means binary logistic regression having binary target variables, but there can be two more categories of target variables that can be predicted by it. Based on those number of categories, Logistic regression can be divided into following types −

1) Binary or Binomial: 

In such a kind of classification, a dependent variable will have only two possible types either 1 and 0. For example, these variables may represent success or failure, yes or no, win or loss etc.

2) Multinomial:

In such a kind of classification, dependent variable can have 3 or more possible unordered types or the types having no quantitative significance. For example, these variables may represent “Type A” or “Type B” or “Type C”.

3) Ordinal:

In such a kind of classification, dependent variable can have 3 or more possible ordered types or the types having a quantitative significance. For example, these variables may represent “poor” or “good”, “very good”, “Excellent” and each category can have the scores like 0,1,2,3.


<p align="center">
  <img width="500" height="300" src="https://miro.medium.com/max/800/0*gKOV65tvGfY8SMem.png">




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
