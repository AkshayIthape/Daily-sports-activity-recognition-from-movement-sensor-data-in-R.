# Daily-sports-activity-recognition-from-movement-sensor-data-in-R.
Deploy Predictive Model for daily/sports activity recognition from movement sensor data in R.

* Reshaping the 3D features to 2D features, performed one-hot encoding on the target variables,
normalizing the range of the features and reducing the high-dimensional features by implementing
PCA.
* Deploying a simple 2 layered neural network model without any regularization and comparing this
model’s performance to the performance of the 2 layered regularized neural network.
* Observing the regularized 2 layered model being better, we compared this with a 3 layered
regularized model and concluding the 3 layered regularized model to be optimal as both had similar
performance.
* Tuning the optimal 2 layered regularized model and finding the optimal values for the hyper
parameters. In the end we successfully obtain a predictive model having an accuracy of 95%.
