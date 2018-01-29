## Abalone Dataset

### Domain
This problem is drawn from the analysis of the data base of the Marine Resources Division. 

The data was received in 1995 and has previously been used for a classification task by Sam Waugh in "Extending and benchmarking Cascade-Correlation", PhD thesis at the Computer Science Department at University of Tasmania as well as a 3-category classification problem by David Clark, Zoltan Schreter, and Anthony Adams in "A Quantitative Comparison of Dystal and Backpropagation".

### Problem Statement
Given the Abalone dataset of sex, length, diameter, height, whole height, shucked height, viscera height, shell weight, and rings, we wish to project the amount of rings based on the other features and perform a classification analysis. Based on the training data set the classification model is supposed to predict the amount of rings based on the features provided.

### Dataset and Inputs
The dataset consists of 9 columns and 4177 rows and requires a memory of 187k GB. Most of the features in the dataset are numeric with the exception of se which is a factor. The target “rings” is an integer. The mean of the target is at 9.93 rings and the most common class is 10 rings. There is a high correlation of the features to the target and even to each other.

### Solution Statement
A solution to this problem will be a classification model such as a logistic regression, a decision tree classifier, or a support vector classifier. As done in previous research it is possible to group various ring classes to simplify the analysis.

### Benchmark Model
Given that we seek a classification model a good naive benchmark would be to guess the most common class or the mean as they are almost the same in this dataset.

### Evaluation Metrics
Given that this is a classification task, and the most common class is in line with the mean of the dataset we can measure the success of our model using the F1 Score or the accuracy.
