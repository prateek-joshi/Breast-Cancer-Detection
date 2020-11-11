# Breast Cancer Detection using Machine Learning
## Background
Breast cancer is the most frequent cancer among women, impacting 2.1 million women each year, and also causes the greatest number of cancer-related deaths among women. In 2018, it is estimated that 627,000 women died from breast cancer – that is approximately 15% of all cancer deaths among women (as taken from WHO). Early detection of breast cancer is possible using Artificial Intelligence and Machine Learning methods. 
## Dataset
The dataset used to train and test the prediction model was obtained from the UCI Machine Learning Repository.
1. https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29
2. https://www.kaggle.com/uciml/breast-cancer-wisconsin-data 

The original dataset has also been uploaded to this repository and can be directly used.
### Description
The dataset consists of the features of a digitized image of a breast cell mass. 
*Attributes information:*
1) ID number
2) Diagnosis (M = malignant, B = benign)

Ten real-valued features are computed for each cell nucleus:

a) radius (mean of distances from center to points on the perimeter) \
b) texture (standard deviation of gray-scale values) \
c) perimeter \
d) area \
e) smoothness (local variation in radius lengths) \
f) compactness (perimeter^2 / area - 1.0) \
g) concavity (severity of concave portions of the contour) \
h) concave points (number of concave portions of the contour) \
i) symmetry \
j) fractal dimension 

For every sample, the *mean, standard error and largest values* (mean of the three largest values) were computed for each image, resulting in a total of 30 features.
## Approach
The original data was cleaned after performing *exploratory data analysis (EDA)*. The cleaned dataset can also be found for direct use in this repository. 
A **Support Vector Classifier (SVC)** was used as the prediction model, in unison with *Grid Search* hyperparameter tuning (with 3-fold cross validation). *recall_score* was used as the scoring parameter, as with medical aplications, we need to have high number of both true and false positives. It is better to have a wrong diagnosis than a missed one.

The final classifier had a recall_score of approximately 0.901, hence further imporovements are required to make the classification even more accurate.
