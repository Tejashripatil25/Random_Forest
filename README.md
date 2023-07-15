![image](https://github.com/Tejashripatil25/Random_Forest/assets/124791646/66f89c61-3678-4d54-9426-e2eb99f402be)

### Random_Forest

![image](https://github.com/Tejashripatil25/Random_Forest/assets/124791646/7a5c9db1-e03d-43f7-aa26-6cf5039ea70d)

Random Forest is an ensemble technique capable of performing both regression and classification tasks with the use of multiple decision trees and a technique called Bootstrap and Aggregation, commonly known as bagging.

The basic idea behind this is to combine multiple decision trees in determining the final output rather than relying on individual decision trees. 

Random Forest has multiple decision trees as base learning models. We randomly perform row sampling and feature sampling from the dataset forming sample datasets for every model. This part is called Bootstrap.

1. Bagging– It creates a different training subset from sample training data with replacement & the final output is based on majority voting. For example,  Random Forest.

2. Boosting– It combines weak learners into strong learners by creating sequential models such that the final model has the highest accuracy. For example,  ADA BOOST, XG BOOST.

![image](https://github.com/Tejashripatil25/Random_Forest/assets/124791646/073b359b-539d-470c-b5ae-f94798ed24df)

### Steps Involved in Random Forest Algorithm

Step 1: In the Random forest model, a subset of data points and a subset of features is selected for constructing each decision tree. Simply put, n random records and m features are taken from the data set having k number of records.

Step 2: Individual decision trees are constructed for each sample.

Step 3: Each decision tree will generate an output.

Step 4: Final output is considered based on Majority Voting or Averaging for Classification and regression, respectively.

random forest voting

![Majority](https://github.com/Tejashripatil25/Random_Forest/assets/124791646/cd91cd8f-4176-4d94-94b3-7d23af601fed)
