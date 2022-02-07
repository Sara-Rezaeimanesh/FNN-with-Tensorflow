# Image-Classifier-FNN-with-Tensorflow
Implemented a FNN with Tensorflow Library that classifies images of animals "elk", "bald eagle", "raccoon" and "raven"." 

## Phase 1
Preprocessing: Onehot encoding

## Phase 2
Building and training a FNN with the following properties:
```
optimizer = SGD
learning rate = 0.01
num of epochs = 10
batch size = 32
activation fuction of all the layers except the last one = relu
activation function of the last layer = softmax
```

## Phase 3 
Hyperparameter Tuning

### Part 1
finding the best momentum: choosing between .5, 1, .8

finding the best otimizer: choosing between SGD, Adam
### Part 2
finding the best number of epochs: choosing between 10, 20, 80, 100
### Part 3
finding the best loss function for classification problems: choosing between MSE, cross entropy
### Part 4
using regularization method and finding the best one: choosing between no regularization, l2, dropoout

## Phase 4
Using the model with the highest accuracy in phase one to classify test data.

## Phase 5
Dimentionality reduction: added an extra layer with 2 neurons before the last layer to be able to display outputs in a 2d plot.
The colored clusters in this plot each represent a different class. The probability of two classes being wrongly classifiend as one another increases the closer the clusters representing the two classes get.
