# Machine Learning Homework - Exoplanet Exploration 
### Hans Engelbrecht

### Initial Observations

This is a model that looks at examining the Kepler Space Telescope data with the goal of identifying hidden planets. This first attempt at building a model is built from the guidence in the initial directions. 

### Preprocess the Data

* Preprocess the dataset prior to fitting the model.
* Perform feature selection and remove unnecessary features.
* Use `MinMaxScaler` to scale the numerical data.
* Separate the data into training and testing data.

### Tune Model Parameters

* Use `GridSearch` to tune model parameters.
* Tune and compare at least two different classifiers.

After looking a little closer at the metrics the model that's described in the directions appears to be very good at seeking out candidates with a .99 f1-score. In terms of identifying actual planets, a false positive is slightly more likely to be identified correctly than a confirmed planet. More modeling will need to be done to determine how best to confirm planets. 