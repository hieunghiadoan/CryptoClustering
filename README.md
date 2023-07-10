# Crypto Clustering

## Overview

The objective of the Crypto Clustering project is to utilize unsupervised learning techniques, specifically K-means clustering, to predict the impact of 24-hour or 7-day price changes on cryptocurrencies. Additionally, the project explores the influence of dimensionality reduction using Principal Component Analysis (PCA) on the clustering process.

## Steps

1. Data loading and preprocessing.
2. Data scaling using StandardScaler.
3. Determining the optimal value for k using the elbow method.
4. Clustering cryptocurrencies with K-means using the original scaled data.
5. Applying PCA to reduce the number of features to three principal components.
6. Identifying the optimal value for k using the PCA-transformed data.
7. Clustering cryptocurrencies with K-means using the PCA-transformed data.
8. Visualizing and comparing the results using hvPlot.

## Results

The project includes the following visualizations:

1. Elbow curve for the original data.

 ![bokeh_plot (5)](https://user-images.githubusercontent.com/117792685/230554676-7874d2ec-2c98-483a-9ec8-b9d48734ea8c.png)

2. Elbow curve for the PCA-transformed data.

![bokeh_plot (6)](https://user-images.githubusercontent.com/117792685/230554807-3b127039-76ba-4bef-a55f-53fcbc34fdb2.png)

3. Scatter plot of cryptocurrency clusters based on the original data.

![bokeh_plot (8)](https://user-images.githubusercontent.com/117792685/230555099-7bbc97d3-e218-49f3-89af-f276e1631ead.png)

4. Scatter plot of cryptocurrency clusters based on the PCA-transformed data.

![bokeh_plot (9)](https://user-images.githubusercontent.com/117792685/230555151-77b912b3-e036-45ad-b7ef-974caf18f869.png)


## Conclusion

This project examines the impact of reducing the number of features on the clustering of data using K-means. By comparing the clustering results obtained from the original data and the PCA-transformed data, we gain insights into the effect of dimensionality reduction on the clustering process.

## Dependencies

- Python
- pandas
- NumPy
- scikit-learn
- hvPlot