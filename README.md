# Stacking Ensemble Technique  for Loan Prediction



Stacking: Universal Dataset<br/>
Stacking technique done with 3 models in level 0 classifier and 1 model in level 1 classifier.<br/>
<br/>
The level 0 classifiers are:<br/>
1. Decision tree using rpart method<br/>
2. Decision tree using C5.0 method<br/>
3. Logistic regression using glm method<br/>
<br/>
The Level 1  classifier is:<br/>
1.The Logistic regression<br/>
<br/>
The Universal Bank dataset has 14 variables and 5000 records. Use “Personal.Loan” as target variable.<br/>
1. Import the data into R<br/>
2. Drop ID & ZIP Code, exp<br/>
3. Convert the attributes to appropriate types.<br/>
4 . Using Equal Frequency Convert numeric attributes into categorical.<br/>
5. Split into Train and Test<br/>
6 . Build several classification models<br/>
7. Predicting on train dataset<br/>
8.Combining the training predictions of all the models.<br/>
9.View the predictions of each model<br/>
10. Add the original target variable to the dataset.<br/>
11.Ensemble the model with GLM as Meta Learner<br/>
12.Check the ensembled model on train data<br/>
13.Follow the steps from 7 to 12 on the test data and check out the accuracy.<br/>
