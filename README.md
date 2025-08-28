# Privacy-and-Fairness
Built a logistic regression model on the Adult Census dataset to predict income levels, with end-to-end data preprocessing, performance evaluation, fairness analysis, bias identification, and implementation of fairness-aware techniques to ensure equitable predictions across demographic groups.

In this assignment we have two parts:
A. You will apply basic privacy techniques to a dataset of your choosing. By the end of this assignment, you should be able to:
1. Understand and implement randomized response on binary data;
2. Calculate the sensititivity of a non-binary feature;
3. Add noise to a non-binary feature;
4. Compute aggregate statistics.

B.You will explore the different fairness metrics learnt in class using a dataset of your choice. Before beginning, you will have to inspect the data and determine the variable of interest (i.e. the outcome) and at least two sensitive features. After each step of your analysis, you will write an in-depth analysis of your results.

This notebook has four stages in which we will:

1. Import the data, implement a few pre-processing steps, and inspect the data
2. Run a short exploratory analysis of the primary variable of interest of your dataset
3. Reproduce the logistic regression model and interpret the estimates
4. Compute the predictive accuracy of the risk score labels
