# Stacking_LoanPrediction



Stacking: Universal Dataset
Stacking technique done with 3 models in level 0 classifier and 1 model in level 1 classifier.

The level 0 classifiers are:
1. Decision tree using rpart method
2. Decision tree using C5.0 method
3. Logistic regression using glm method

The Level 1  classifier is:
1.The Logistic regression

The Universal Bank dataset has 14 variables and 5000 records. Use “Personal.Loan” as target variable.
1. Import the data into R
2. Drop ID & ZIP Code, exp
3. Convert the attributes to appropriate types.
4 . Using Equal Frequency Convert numeric attributes into categorical.
5. Split into Train and Test
6 . Build several classification models
7. Predicting on train dataset
8.Combining the training predictions of all the models.
9.View the predictions of each model
10. Add the original target variable to the dataset.
11.Ensemble the model with GLM as Meta Learner
12.Check the ensembled model on train data
13.Follow the steps from 7 to 12 on the test data and check out the accuracy.
