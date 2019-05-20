# Facebook-Comment-Volume-Classification
This data set contains information related to user comments on the Facebook and the effort has been made to design a model using Supervised learning algorithms to classify a given post that would receive a comment within or more than an hour. I have used Support Vector Machines (Linear, Polynomial with various degree, and Sigmoid kernels), Decision Trees (Entropy), and Boosting (AdaBoost) to train the model and get optimum results.

# Performance of SVM(Linear kernel)
The goal is to understand how the hyperparameter C affects the classification by changing it. For different C values; the accuracy is recorded and shown in the below table
![LinearSVMDAtaset1](https://user-images.githubusercontent.com/45961950/58058862-43580780-7b30-11e9-8dac-5b9ff807a52f.PNG)

# Polynomial Kernel
As we increase the degree of polynomial kernel, we observe that the accuracy goes on decreasing
![Dataset1_AccuracyPlotforPoly](https://user-images.githubusercontent.com/45961950/58058986-ba8d9b80-7b30-11e9-9731-4c841a9c590b.png)

# Decision Tree
Performance of Decision tree on Train, Validation and Test data
![Dataset1_TVT_GainDTree](https://user-images.githubusercontent.com/45961950/58059016-db55f100-7b30-11e9-986e-97dad46df5b9.png)

# Overall Accuracy of models
![accuracyofallmodelsDat1](https://user-images.githubusercontent.com/45961950/58059105-148e6100-7b31-11e9-949b-89386de8d817.PNG)
