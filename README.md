# Predicting the Likelihood of E-Signing a Loan Based on Financial History


Lending companies work by analyzing financial history of their loan applicants, and choosing whether or not the applicant is too risky to be given the loan.If applicant is not , the comapny then determines the terms of the loan. To acquire these applicants,companies recieve this information through their website/apps. Other times ,lending companies work with lending marketplaces, in order to acquire leads of possible applicants.

Goal : Develop an model to predict for 'quality' applicants. In this case, 'quality' applicants are those who reach a key part of the loan application process.

Data : The data includes personal information like age,and time employed as well as other financial metrics. Both the sets of scores as well as small list of personal/financial features to predict if the user will repond to our current onboarding process.

Model : It makes sense to use logistics regression here as we’re trying to predict a binary outcome. Also SVM (Linear) , SVM (RBF) and Random Forest model were implemented. Observing the results from these models, we use grid search (GridSearchCV) with different parameter/value combinations to tune our model for even better results.

The optimized model (Random Forest (n=100, GSx2 + Gini)) has an accuracy of 0.6413.




