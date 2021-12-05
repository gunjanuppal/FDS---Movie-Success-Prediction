# FDS---Movie-Success-Prediction
To predict a movie’s success, four classification algorithms are used: logistic regression, K-nearest neighbors, decision tree, and random forest. Each classification algorithm will be using the same target value and predictors. The target value is success, a boolean value that is true if the revenue exceeds twice the budget. The predictors are listed below:

‣budget – total money required to produce movie

‣runtime – total movie time in minutes

‣year – release year

‣vote_average – mean community score

‣vote_count – number of votes attributing to vote_average

‣genre – most significant genre

‣country – most significant production country

‣certification_US – movie rating that determines suitability by viewer age

For the categorical predictors (genre, country, certification_US), dummy variables are created so the algorithm can process them. For each algorithm, sklearn’s grid search is used to find the hyper-parameters with the best accuracy. The grid search also uses a k-fold cross-validation where k=10 to ensure that the entirety of the dataset is tested. The model accuracy is measured using the mean of the test scores from the cross-validation. The mean training score will also be shown to determine if the model is overfitted or underfitted

The main task is to compare all the 4 machine learning algorithm and find out which fits best based on accuracy, mean training score, mean testing score and hyper-parameters.

Group Members:
1. Gunjan Uppal (2018A7PS0087U)
2. Toshal Shankarshetty (2018A7PS0072U)

Supervisor:
Dr. Siddhaling Urolagin,
PhD, Post-Doc, (Machine Learning),
dr.siddhaling@gmail.com,
www.github.com/siddhaling
www.researchreader.com
