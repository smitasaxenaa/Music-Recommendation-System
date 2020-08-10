# Music-Recommendation-System-using-Python


The training data set provided by KKBOX consists of information of the first observable listening event for each unique user-song pair within a specific time duration. Metadata of each unique user and song pair is also provided. The train and the test data are selected from users listening history in a given time period. This time period is chosen to be before the WSDM-KKBox Churn Prediction time period. The train and test sets are split based on time, and the split of public/private are based on unique user/song pairs.

First exploratory data analysis and data visualisation is performed to pre-process the data for building the model. The Random Forest Classifier is used to build a music recommendation model with a prediction accuracy of 73.16 %.

