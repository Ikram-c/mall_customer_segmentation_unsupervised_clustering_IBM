# Mall Customer Segmentation Unsupervised clustering project




## Overview of project
The aim of this project was to look for ways to ***cluster*** two segments of data together for a hypotehtical business to make better business decisions. The data was sourced from the "Mall Customer Segmentation Data" dataset from kaggle (https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)

Data was imported from a CSV into a Pandas dataframe and EDA was conducted to find nulls, the distribution (using a ***Pairplot***) and finding any outliers with a boxplot.

Outliers were managed using two different methods: the first was to check for datapoints that are more than three standard deviations from the mean and then flagging the values (this did not yield usuable results). The second method used the upper and lower boundary technique (which fixed the outlier).

A scatter plot was produced to see if clusters could be visually identified before using any machine learning algorithms and 5 distinct clusters were observed.

The following Unsupervised classification models were then used:
- ***KMeans***
- ***Meanshift***
- ***DBScan***

***PCA*** was then conducted to try to improve the performance of the algorithms and the same models were then ran again.
Models were assessed through their own scatterplots as well as their Silhouette score.

A detailed breakdown can be found in the notebook

N.B. This project was peer assessed on coursera as part of my final project for my IBM unsupervised ML certificate

