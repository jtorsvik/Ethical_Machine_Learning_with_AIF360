# Ethical-Machine-Learning-with-AIF360
Using algorithms from IBM's AIF360 library to reduce disparities between unprivileged- and privileged groups in two datasets with their own unique classification problem:

1. German Bank Credit Scores
    The goal will be to classify whether customers are "good" (1) or "bad" (2). This could determine whether the customers will get a loan from the bank or not. Due to     the potential cost of making a mistake, it will be worse to classify a customer as "good" when they are "bad" than the other way around. 
    https://archive.ics.uci.edu/ml/datasets/statlog+(german+credit+data)

2. A census made in USA in 1994
    Based on the features made in the census, the goal will be to classify whether the individual is making more or less than $50K per year.
    https://archive.ics.uci.edu/ml/datasets/adult

## Purpose of the Project

The focus in this project will be on gender, but this can easily be changed to other groups such as age, ethnicity (race) and country of origin. The two datasets have been altered to highlight disparities and inequalities between unprivileged and privileged groups. 

The first phase in this project is to show how the unaltered datasets' privileged-, and unprivileged groups are affected by a regular classification using the Random Forest Classifier and hyper-parameter tuning with conventional accuracy metrics such as Accuracy, Recall and F1-score.

The second phase will attempt to reduce Equal Opportunity differences as much as possible by implementing Exponentiated Gradient Reduction in the classifier.

The third and final phase will attempt to combine phase 1 and 2 by optimizing the accuracy of the model, as well as reducing Equal Opportunity differences between the two groups.
