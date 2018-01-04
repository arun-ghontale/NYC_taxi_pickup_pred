# New York Taxi Pickup Prediction
Given a latitude and longitude of a taxi along with other information such as current month, date and time and fourier components of the time series training data, the task was to estimate the pickup density.
Data available at - http://www.nyc.gov/html/tlc/html/about/trip_record_data.shtml

In order to evaluate the performance of our model, I split the data into a training set (80% of data set) and testing set (20% of data set) , where the training examples are all ordered chronologically before the testing examples. This configuration mimics the task of predicting future numbers of taxi pickups using only past data.

I chose RMSE to evaluate our prediction because it favors consistency and heavily penalizes predictions with a high deviation from the true number of pickups.

Also, to improve upon this result by using Neural Networks or K-means Clustering in order to find non-obvious patterns across data points, we could use unsupervised learning to cluster our training set. 
