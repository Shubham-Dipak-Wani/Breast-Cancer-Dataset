
## Breast Cancer Dataset


#### Context:

This repository contains a dataset for breast cancer detection, which can be used for machine learning and data analysis projects. 

#### Dataset
The dataset contains information on various features of breast mass images, such as radius, texture, perimeter, area, smoothness, compactness, concavity, concave points, symmetry, and fractal dimension. There are 569 instances in the dataset, each with a unique ID and a label indicating whether the mass is malignant or benign.
#### Data Files

The dataset is available in file:

data.csv: This is the main dataset file containing all the features and labels. Each row represents a unique instance and contains the following columns:

id: The unique ID of the instance.

diagnosis: The label indicating whether the mass is malignant (M) or benign (B).

radius_mean, texture_mean, perimeter_mean, area_mean, smoothness_mean, compactness_mean, concavity_mean, concave points_mean, symmetry_mean, fractal_dimension_mean: The mean value of each feature for the instance.

radius_se, texture_se, perimeter_se, area_se, smoothness_se, compactness_se, concavity_se, concave points_se, symmetry_se, fractal_dimension_se: The standard error of each feature for the instance.

radius_worst, texture_worst, perimeter_worst, area_worst, smoothness_worst, compactness_worst, concavity_worst, concave points_worst, symmetry_worst, fractal_dimension_worst: The worst or largest value of each feature for the instance.
