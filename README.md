# Bike Rental Regression Study

Here I present a study of Seoul bike rental data, taken from the ICU Machine Learning Repository:

    https://archive.ics.uci.edu/ml/datasets/Seoul+Bike+Sharing+Demand.

This dataset provides hourly entries over 365 days spanning 01/12/2017-30/11/2018. Each entry provides the number of rented bikes, as well as a collection of weather and time conditions for the given hour. Naturally it is important to predict and supply a stable number of bikes to minimise wait times. It is also useful to know when less bikes can be deployed which allowing time for bike maintinance.

In this study I will build a regression model to study how well the provided features can predict bike rentals. This notebook will in addition answer some additional questions I find interesting:

1. Can we evaluate an uncertainty on the prediction.
2. Can additional features be engineered or introduced to improve prediction
3. Can an estimate be provided for the current hour? This will involve dealing with some feature being inaccessible and hence usage of imputation will be required.

