# Cryptocurrencies

## Purpose

The purpose of this project was to search for unknown patterns in data using unsupervised machine learning and create 3D visualisations and scatterplots with plotly.explress and hvplot.

The data set was provided for this project.

The whole process was broken down to several steps:

1) The data was preprocessed for principal component analysis (PCA), unnecessary columns removed, null values dropped, StandardCScaller was used to standardize the features in DataFrame
2) Data Dimensions reduced using PCA
3) Data clustered using K-means algorithm, number of centroids for K-means determined using the elbow curve
4) Visualisations created as follows. See below:

![3D](https://github.com/AlekseiPronin/Cryptocurrencies/blob/main/Resources/newplot.png)


![hvplot](https://github.com/AlekseiPronin/Cryptocurrencies/blob/main/Resources/bokeh_plot.png)
