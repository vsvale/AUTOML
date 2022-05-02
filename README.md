# AUTOML

* AutoML algorithms aren't intended to run for only a few minutes
* AutoML algorithms can take a long time to finish their search
* AutoML algorithms can recommend different solutions for the same datase

## Tools Tested

TPOT is a data-science assistant which optimizes machine learning pipelines using genetic programming.
http://epistasislab.github.io/tpot/

Auto-sklearn is an automated machine learning toolkit and a drop-in replacement for a scikit-learn estimator.
https://automl.github.io/auto-sklearn/master/

TPOT is a Python Automated Machine Learning tool that optimizes machine learning pipelines using genetic programming.
http://epistasislab.github.io/tpot/

## Dataset
https://archive.ics.uci.edu/ml/datasets/wine
These data are the results of a chemical analysis of wines grown in the same region in Italy but derived from three different cultivars. The analysis determined the quantities of 13 constituents found in each of the three types of wines.

I think that the initial data set had around 30 variables, but for some reason I only have the 13 dimensional version. I had a list of what the 30 or so variables were, but a.) I lost it, and b.), I would not know which 13 variables are included in the set.

The attributes are (dontated by Riccardo Leardi, riclea '@' anchem.unige.it )
1) Alcohol
2) Malic acid
3) Ash
4) Alcalinity of ash
5) Magnesium
6) Total phenols
7) Flavanoids
8) Nonflavanoid phenols
9) Proanthocyanins
10)Color intensity
11)Hue
12)OD280/OD315 of diluted wines
13)Proline

In a classification context, this is a well posed problem with "well behaved" class structures. A good data set for first testing of a new classifier, but not very challenging.

https://archive.ics.uci.edu/ml/machine-learning-databases/wine/wine.data

## Objective
Generate classification models via automl
