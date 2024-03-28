# Confusion-_-matrix

## Confusion Matrix in Machine Learning
In machine learning, classification is the process of categorizing a given set of data into different categories. In machine learning, to measure the performance of the classification model, we use the confusion matrix. Through this tutorial, understand the significance of the confusion matrix.

## what is a Confusion Matrix?
A confusion matrix is a matrix that summarizes the performance of a machine learning model on a set of test data. It is a means of displaying the number of accurate and inaccurate instances based on the model’s predictions. It is often used to measure the performance of classification models, which aim to predict a categorical label for each input instance.

The matrix displays the number of instances produced by the model on the test data.

True positives (TP): occur when the model accurately predicts a positive data point.
True negatives (TN): occur when the model accurately predicts a negative data point.
False positives (FP): occur when the model predicts a positive data point incorrectly.
False negatives (FN): occur when the model mispredicts a negative data point.

## Why do we need a Confusion Matrix?
When assessing a classification model’s performance, a confusion matrix is essential. It offers a thorough analysis of true positive, true negative, false positive, and false negative predictions, facilitating a more profound comprehension of a model’s recall, accuracy, precision, and overall effectiveness in class distinction. When there is an uneven class distribution in a dataset, this matrix is especially helpful in evaluating a model’s performance beyond basic accuracy metrics.

# Confusion Matrix For binary classification

![image](https://github.com/Rohitbachchhe17/Confusion-_-matrix/assets/163370274/6e51308a-484c-42c3-81bc-8d4140bf2a6d)


- True Positive (TP): It is the total counts having both predicted and actual values are Dog.
- True Negative (TN): It is the total counts having both predicted and actual values are Not Dog.
- False Positive (FP): It is the total counts having prediction is Dog while actually Not Dog.
- False Negative (FN): It is the total counts having prediction is Not Dog while actually, it is Dog.


# matrix based confusion matrix data 
![image](https://github.com/Rohitbachchhe17/Confusion-_-matrix/assets/163370274/2b8aa90c-c5d3-42f4-98b8-b89b22f702f1)



