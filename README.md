# Breast Cancer Detection using Machine Learning Techniques
## Background
Breast cancer is the most frequent cancer among women, impacting 2.1 million women each year, and also causes the greatest number of cancer-related deaths among women. In 2018, it is estimated that 627,000 women died from breast cancer – that is approximately 15% of all cancer deaths among women (as taken from WHO). Early detection of breast cancer is possible using Artificial Intelligence and Machine Learning methods. 
## Dataset
The dataset used to train and test the prediction model was obtained from the UCI Machine Learning Repository.
1. https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29
2. https://www.kaggle.com/uciml/breast-cancer-wisconsin-data (Can also be downloaded from Kaggle.)

The original dataset has also been uploaded to this repository and can be directly used.
### Description
The dataset consists of the features of a digitized image of a breast cell mass. 
Attributes information:
1) ID number
2) Diagnosis (M = malignant, B = benign)

Ten real-valued features are computed for each cell nucleus:

a) radius (mean of distances from center to points on the perimeter)_
b) texture (standard deviation of gray-scale values)
c) perimeter
d) area
e) smoothness (local variation in radius lengths)
f) compactness (perimeter^2 / area - 1.0)
g) concavity (severity of concave portions of the contour)
h) concave points (number of concave portions of the contour)
i) symmetry
j) fractal dimension 

For every sample, the mean, standard error and largest (mean of the three largest values) were computed for each image, resulting in a total of 30 features.
## Approach
The original data was cleaned after performing exploratory data analysis (EDA). The cleaned dataset can also be found for direct use in this repository. 
