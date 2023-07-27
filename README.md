# Kaggle competition - Santander Customer Satisfaction dataset

The notebook is a solution for the Kaggle competition where the objective is to predict churn among unhappy customers: https://www.kaggle.com/competitions/santander-customer-satisfaction/overview

The approach used here is a feature selection to pick among more than 300 features that are most suitable for the problem since we don't know the business meaning of the features. After the feature selection, we need to choose a model and its parameters. Normally, the tool for this task is the GridSearch method, which can be computationally expensive and take a long time. The alternative here is hyperopt, a Bayesian optimization for parameter search. After Kaggle submission, we can see in the notebook that this process results in a score similar to the leaderboard without the need to create features or balance classes synthetically.
