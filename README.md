
Machine learning approach of prediction of flood depending on previous year rainfall data.

An accuracy of 86.08 % is obtained just by taaking 3 features.
If more features like the topography type and land features are added then the accuracy can be improved.
We use logistic regression to train the model

We have predicted floods just for the state of kerala depending on the rainfall data. However this method can be used for prediction for any state of india, with the given data.

The input features used are the average rainfall in the month of marhc to may , the average rainfall in first 10 days of june and the inscrease in rainfall from the month of may to june, for all the years from 1901 to 2015

We used the months march, april, may and june to predict food in the later days of the month of june and july, as in keral the rainy season starts from the month of june. 
Depending on other states, other months will be used as the features.

A dataset with the amount of rainfall and if a flood had occured in a particular area/state/city, in the previous years, will be used. The dataset will have the rainfall data for a duration of 3 months approx.

Using this dataset, we take average rainfall for every 10 days and plot it on a graph to visualize it.
We take this average data of rainfall, as input to our machine learning model and if it causes a flood or not as the output labels.
We train our model and save it.(depending on some threshold value of average rainfall in the dataset)

Given the input data, for consecutive 10 days, we give this data as an input, and let the model predict, if whether there is a possibility of flooding or not, by setting some threshold in the training data. 
Our basic approach for this problem is binary classification, using basic machine learning algorithms(linear regression or logistic regression).

This approach can be made real time prediction and accuracy can be improved with adding more features such as the type of land in that area, the location of the area etc.
