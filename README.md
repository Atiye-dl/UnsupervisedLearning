# UnsupervisedLearning
Clustering with K-means, DBscan, and MeanShift on a dataset of celebrities photo based on python

The dataset of this code consists of 50,000 images of celebrities, which are included in a csv file.
Each row in this csv file is assigned to a specific image and contains one or more different facial features that are encoded in binary (- 1 or 1).
There is also a test dataset consisting of 100 other images as a test file.

The first phase is Feature Extraction, in which the approximate eye and skin color of each image is found.

The second phase is Feature Selection, which is specified by 6 features. From the csv file, the correlation value between each feature is calculated and a correlation matrix is ​​created.

The third phase is related to Clustring.

The fourth phase is related to Vizualization and data reduction.

In the fifth phase, the centers of the clusters are found by the K-means algorithm, and then 50 data points near each center of each cluster are found by KNN and checked whether it belongs to the correct cluster or not.

In the sixth phase, the Prediction operation is performed on the data. The final results are compared and finally plotted.
