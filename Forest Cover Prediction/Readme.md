It is a Kaggel competition:
In this competition you are asked to predict the forest cover type (the predominant kind of tree cover) from strictly
cartographic variables (as opposed to remotely sensed data). The actual forest cover type for a given 30 x 30 meter cell 
was determined from US Forest Service (USFS) Region 2 Resource Information System data. Independent variables were then
derived from data obtained from the US Geological Survey and USFS. The data is in raw form (not scaled) and contains binary 
columns of data for qualitative independent variables such as wilderness areas and soil type.

This study area includes four wilderness areas located in the Roosevelt National Forest of northern Colorado. 
These areas represent forests with minimal human-caused disturbances, so that existing forest cover types are more 
a result of ecological processes rather than forest management practices.
The training set (15120 observations) contains both features and the Cover_Type. 
The test set contains only the features. You must predict the Cover_Type for every row in the test set (565892 observations).


# In this

problem i have used Random Forest Classifier to predict the cover type of Forest's id.

First i got the accuracy arround 78% . But after the model tuning i got 85.89% on test set.

Lanuage used: Python with Sklearn

Visualization: Pandas

Algorithm: Random Forest Classifier

Accuracy: 85.89%


