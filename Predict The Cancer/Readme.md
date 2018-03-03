# Predict whether the cancer is benign or malignant

Features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. 
They describe characteristics of the cell nuclei present in the image. n the 3-dimensional space is that
described in: [K. P. Bennett and O. L. Mangasarian: "Robust Linear Programming Discrimination of Two Linearly 
Inseparable Sets", Optimization Methods and Software 1, 1992, 23-34].

About dataset:

Attribute Information:

1) ID number 2) Diagnosis (M = malignant, B = benign) 3-32)

Ten real-valued features are computed for each cell nucleus:

a) radius (mean of distances from center to points on the perimeter) b) texture (standard deviation of gray-scale values) c) perimeter d) area e) smoothness (local variation in radius lengths) f) compactness (perimeter^2 / area - 1.0) g) concavity (severity of concave portions of the contour) h) concave points (number of concave portions of the contour) i) symmetry j) fractal dimension ("coastline approximation" - 1)

The mean, standard error and "worst" or largest (mean of the three largest values) of these features were computed for each image, resulting in 30 features. For instance, field 3 is Mean Radius, field 13 is Radius SE, field 23 is Worst Radius.

All feature values are recoded with four significant digits.

Missing attribute values: none

Class distribution: 357 benign, 212 malignant


In this problem i have to predict whether the Breast Cancer is benign or malignant.

I have used Random Forest algorithm in this task and got the accuracy arround 95% .

But after the tuinig the model parameters i got accuracy arround 97.90 %  which is pretty good.
Technology used:
Python with Sklearn
Algorithm: Random Forest
Visualization by Pandas 
acuuracy: 97.90%
Data source: https://www.kaggle.com/uciml/breast-cancer-wisconsin-data
My kernal: https://www.kaggle.com/dhamashivam/breast-cancer-classification-by-random-forest
