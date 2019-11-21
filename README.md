# IMDB Sentiment Analysis with SageMaker

* [IMDB Sentiment Analysis - XGBoost (Batch Transform)] constructs a model using XGBoost to perform sentiment analysis on the IMDB dataset.
* [IMDB Sentiment Analysis - XGBoost (Hyperparameter Tuning)] constructs a sentiment analysis model using XGBoost and using SageMaker's hyperparameter tuning functionality to test a number of different hyperparameters.
* [IMDB Sentiment Analysis - XGBoost (Updating a Model)] constructs a sentiment analysis model using XGBoost, explors what happens if something changes in the underlying distribution, constructs an updated model and then updates a deployed endpoint so that it makes use of the new model.
* [IMDB Sentiment Analysis - XGBoost - Web App] creates a sentiment analysis model using XGBoost, deploys the model to an endpoint, and sets up AWS Lambda and API Gateway to create a simple web app that interacts with the deployed endpoint.
