# Machine_Learning_Portfolio_2024_S2

Forest Fire Prediction Using K-Nearest Neighbours and Linear Regression Project Summary This is a repository created for two machine learning models, K-Nearest Neighbors, and Linear Regression, developed for the estimation of forest fires. The project offers an example of how the algorithms could be used in solving a real-world problem like the occurrences of forest fires from different factors of the environmental set-up.

Dataset
In the given project, the data set contains several environmental parameters such as temperature, humidity, wind speed, and rainfall, which are usually major predictors in case of a forest fire. The preprocessing of data includes treating missing values and scaling for the better performance of models.

Models
1. K-Nearest Neighbors (KNN)
KNN is a non-parametric algorithm that classifies data points by considering similarities with their nearest neighbors. Here, the KNN will be implemented to classify areas as either in fire-risk or not, based on historical data.

Hyperparameters:

Number of Neighbors - k
Distance Metric (Euclidean, Manhattan, etc.)
Evaluation Metrics:

Accuracy
Confusion Matrix
Precision, Recall, F1-Score
2. Linear Regression
Linear Regression is a parametric algorithm that models the relationship between a dependent variable and one or more independent variables. In the given project, it will be used to predict the area of forest that will be affected by fire based on environmental factors.

Hyperparameters:

Regularization (L2)
Learning Rate
Evaluation Metrics:

Mean Squared Error (MSE)
R-squared (R²)
