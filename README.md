# Google Earth Engine and Machine Learning

## Introduction
In this project, I was tasked to perform unsupervised classification to a country’s landcover data, provided with some validated data point in forms of CSV and a Python list of bounding box. In this case, I used K-Means clustering algorithm for landcover data in the Netherlands. The code was written in Jupyter Notebook and stored publicly in Github repository.

All provided data were being read using GeoPandas dataframe and converted into Google Earth Engine’s feature collections. GEE Python API was used to retrieve Sentinel S2 satellite images based on the bounding box and date filter. Image processing was performed using geemap Python package. K-means clustering was performed using ee.Clusterer package.

After the classification, the result is validated using provided validated data points and visualized in histogram. The same trained model were also used in different country (Germany) to check the performance.

## Implementation
Open the Jupyter Notebook 'gee_kmeans.ipnyb' and run the cells accordingly.
