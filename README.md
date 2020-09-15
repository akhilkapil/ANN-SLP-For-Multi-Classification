# ANN-SLP-For-Multi-Classification

Introduction to the dataset: We have seven classes in the dataset wfor which we will be using ANN/SLP(Single Layer Perceptron) model with Softmax Regression Function.

Why Softmax Function ? 
Because Softmax regression (or multinomial logistic regression) is a generalization of logistic regression to the case where we want to handle multiple classes. In logistic regression we assumed that the labels were binary: y(i)∈{0,1}. We used such a classifier to distinguish between two kinds of hand-written digits. Softmax regression allows us to handle y(i)∈{1,…,K} where K is the number of classes.

Recall that in logistic regression, we had a training set {(x(1),y(1)),…,(x(m),y(m))} of m labeled examples, where the input features are x(i)∈Rn. With logistic regression, we were in the binary classification setting, so the labels were y(i)∈{0,1}. Our hypothesis took the form:

hθ(x)=11+exp(−θ⊤x)
