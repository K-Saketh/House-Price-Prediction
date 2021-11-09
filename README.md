1) Question the data - Understand the variables very carefully and formulate your questions/hypothesis. (Note that these are just your initial hypothesis which may or may not seem to be true after the EDA step)

2) EDA - explore the dataset very carefully. Do univariate analysis and bivariate analysis by choosing appropriate graphs, charts and descriptive measures. Report the surprising elements (i.e. the one which you believed would be true in step 1 did not turn out t be true, or a result that was beyond your expectation, etc.)

3) Initial model fitting step - FIt a couple of linear regression models by considering different sets of predictors on the training dataset. Argue the reasons for considering those predictor sets. Report 10-fold cross-validation RMSE and R-squared values. Discuss the results.

4) Feature engineering - (A) Suggest some possible feature transformations (like log(X), sqrt(X), X^2, X1*X2, etc.) with reasons, which you believe could have improved the performances of the previous models. Experiment to check if such transformations actually help to do so. (B) suggest some new feature generation techniques (e.g. creating dummy variables, or using one-hot encoding, or transforming an existing feature to a new feature as you may convert the variable 'year built' to the 'age of the house'. Check if such transformations help in improving the performances of the models. Report the RMSE and R-squared values in each case.

5) Model fitting step 2 - You may use model selection methods like (forward selection or backward elimination methods) to select an appropriate model.

6) Model fitting step 3 - Experiment and check if a decision tree model can be used to fit the data mode accurately. You are free to use any kind of hyperparameter tuning to fit the model. Experiment using all the feature sets you have created before (including all the transformed sets and new feature-generated sets).

7) Model testing - Consider the best competing models and test their performances on the test data. Report the results.
