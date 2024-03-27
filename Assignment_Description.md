In this project you will be working with two or three datasets of your choice. You will be exploring these datasets, finding a meaningful target variable, finding suitable explanatory variables, and investigating the suitability of logistic regression or SVMs to them.

This project is set up a little different than other projects. In your group you will together select 2-3 datasets, one for each person in the group. Then each person in the group will take responsibility for one of the datasets, exploring the questions discussed below, and then explaining their results to the remainder of the group. If one of your group members is selected to present on your work, they will be expected to describe and explain all 2-3 datasets, so make sure you get together and explain your work to each other! While one person is responsible for one dataset, that doesn't mean they have to do it all alone -- I suggest that you check in with each other periodically with questions and thoughts.

Your datasets should be suitable for logistic regression and SVMs. That is, they should have at least one variable that could be a target categorical variable. The remaining variables you will consider for explanatory variables can be categorical or quantitative, but your analysis might be a little easier if you choose quantitative variables. The target variable must have at least two classes, but be careful that it doesn't have too many classes or your predictive and runtime performance might suffer. Questions you should ask could include (but are not limited to):

    Which variables are predictive of the target variable?
    Can logistic regression or a linear SVM predict well?
    What do plots of selected pairs of variables look like? Where is the decision boundary in those plots?
    How generalizable are the different models on your data? How does the bias-variance tradeoff affect which model you might choose?
    Is there a difference between the polynomial and RBF SVMs?
    What effect does changing the class_weight in an SVM have on your data? How might this be important for this data?
    Is there a difference in runtime performance?
    Logistic regression and LinearSVC use one-vs-rest (OVR) for multi-class classification. SVC uses one-vs-one (OVO). Where n is the number of classes, OVR learns n models, whereas OVO learns n(n-1)/2 (n choose 2) models. What effect does this have on performance?

Your project report should have an introduction and then one section for each dataset, discussing it and the methods used on it. The datasets need not be related to each other.