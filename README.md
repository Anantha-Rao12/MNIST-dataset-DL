# MNIST-dataset-DL
Python script for Feedforward ANN on MNIST dataset

Training set --> 60000
Test set --> 10000

Hyperparameters:
1) No of dense layers : 1
2) Activation functions : ReLU --> Softmax
3) Dropout percent (for regularisation) --> 20%
4) Optimizer : SGD 
5) Loss function = Sparse categorical crossentropy
6) Epochs: 500 (Validation error is seen to plateau around 130epochs --> probable overfitting) 

FINAL LOSS:
1) Train set --> 0.0109
2) Validation set --> 0.0667
3) Test set --> 0.0666

FINAL ACCURACY:
1) Train set --> 99.69%
2) Validation set --> 98.16%
3) Test set --> 98.16%

===>> This gap between training accuracy and test accuracy represents overfitting
===>> Confusion Matrix says that most misclasified labels were 2-->7 and 3-->5

