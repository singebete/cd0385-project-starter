# Report: Predict Bike Sharing Demand with AutoGluon Solution
#### Louis Byers

## Initial Training
### What did you realize when you tried to submit your predictions? What changes were needed to the output of the predictor to submit your results?
First I realized that the test set didn't include 2 features ('casual' and 'registered') that I used to train the initial models. So I had to drop those columns from the training set and retrain the models. I also had to verify that the test set datetime matched the submisttions datetime so the predictions would match up.

### What was the top ranked model that performed?
It was the `WeightedEnsemble_L2` but it seemed marginally better than 2nd place `RandomForestMSE_BAG_L2` or even `ExtraTreesMSE_BAG_L2` at least according the RMSE.

## Exploratory data analysis and feature creation
### What did the exploratory analysis find and how did you add additional features?
TODO: Add your explanation

### How much better did your model preform after adding additional features and why do you think that is?
TODO: Add your explanation

## Hyper parameter tuning
### How much better did your model preform after trying different hyper parameters?
TODO: Add your explanation

### If you were given more time with this dataset, where do you think you would spend more time?
TODO: Add your explanation

### Create a table with the models you ran, the hyperparameters modified, and the kaggle score.
|model|hpo1|hpo2|hpo3|score|
|--|--|--|--|--|
|initial|?|?|?|?|
|add_features|?|?|?|?|
|hpo|?|?|?|?|

### Create a line plot showing the top model score for the three (or more) training runs during the project.

TODO: Replace the image below with your own.

![model_train_score.png](img/model_train_score.png)

### Create a line plot showing the top kaggle score for the three (or more) prediction submissions during the project.

TODO: Replace the image below with your own.

![model_test_score.png](img/model_test_score.png)

## Summary
TODO: Add your explanation
