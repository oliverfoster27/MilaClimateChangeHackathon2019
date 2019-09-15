# MilaClimateChangeHackathon2019
 Repo to track progress in 2019 Mila Climate Change Hackathon

# Ideas
- Use precipitation data from Montreal to predict accidents over the period of 2012-2017
- Use this model to forecast total car accidents that will occur in the future
- Potentially only look at winter months 

# Contents/Glossary

### Clean Data.ipynb
- Clean precipitation data to be merged later to the accident data

### Create Future Validation Set.ipynb
- Create future set to be used to forecast accident data from 2018-2100

### Linear Regression.ipynb
- Train Linear Regression algorithm on data as baseline

### Merge Data.ipynb
- Merge the accidents and precipitation datasets to be sent to training

### Mila2019ClimateChangeHackathon_DNN.ipynb
- Training of a Dense Neural Network on predicting # of incidents based on location, time, and precipitation

### Summary_Results_CC
- Jupyter notebook depicting the average results for each of the possibly target variables. Code includes a table that outlines the averages for targt variables from the testing set coming from the test-train set.

### Forests_ClimateChange
- Random Forest and Gradient Boosting Forest Regressors to predict the output of Number of Incidents – Notebook includes the test-train splits, the GridSearch hyper tuning parameters and the Mean Absolute Error for the random forest and gradient boosting forest results.

### RF_Script
- Random Forest script – for looping all the possible target values and outputting in dataframe the regressor scores ( Mean Absolute Error / Average for each possible target variable).



