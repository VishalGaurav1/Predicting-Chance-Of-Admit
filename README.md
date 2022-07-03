# Predicting-Chance-Of-Admit
This repository deals with predicting the Chance Of Admit of a student .
Insights:
1)Target variable(Chance of Admit) has strong correlation with CGPA score(0.88) and high correlation with GRE score(0.81) and TOEFL score(0.79).
2)It is seen that Chance of Admit is higher for the students studying in universities with higher rating.Also students who have done research have a higher chance of admit than the student who have not done research.
3)Performing Linear Regression to predict the chance of admit of a student resulted in the R squared score of 0.79 on test data.
4)Performing Linear regression after removing outliers does not increase the performance of the model.Therefore I think that the outliers have no major impact.
5)Then I perormed ensemble techniques for this project and R squared score was highest for RandomForest Regressor at 0.81.
6)The most important features which will play a key role in deciding the Chance of Admit of a student are CGPA score and GRE score while the least important features are LOR and Research.
