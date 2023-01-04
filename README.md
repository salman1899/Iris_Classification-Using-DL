Feed-Forward Neural network is a class of Artificial Neural Network and its using the back propagation techinque, This model has one hidden layer in hidden layer it has 3 perceptrons. During training, all the weights and biases are updated after processing training samples and the method is called mini-batch Gradiant Optimization method. The code is run almost 220 epochs. The activation function is softmax Because for multiclass problems we have to use softmax activation function. The performance of classification is measured using confusion matrix. The code computes specificity, sensitivity, precision, recall, accuracy and F1-score. The dataset load from the sklearn package and its divided into 2 folds wherein 1 subsamples are used to train the network and the 2nd subsample for tests the model.

1. Algorithm runs 150 epochs with softmax activation function and batch size is 7 optimizer is adam in one hidden layer the output's are accuracy is0.66666
 and the loss is 0.444444  confusion matrix = [11,  0,  0],[ 0,  1,  0],[ 0, 12,  6], and for class 0 - f1 score is 1.0 , precision is 1.0 and recall is 1.0 support is 11 for class 1 - f1 score is 0.14 , precision is 0.08 and recall is 1.00 support is 1 for class 2 f1 score is 0.50 , precision is 1.0 and recall is 0.33 support is 18 
 
2. Algorithm runs in 210 epochs with softmax activation function and the batch size is 7, optimizer is adam runnig in one hidden layer and input dimentions are 4 the output's are accuracy is
 0.99 and the loss is 0.01
 
 classification report
     precision    recall  f1-score   support

           0       1.00      1.00      1.00        11
           1       0.77      1.00      0.87        10
           2       1.00      0.67      0.80         9

    accuracy                           0.90        30
   macro avg       0.92      0.89      0.89        30
weighted avg       0.92      0.90      0.90        30

confution matrix
array([[11,  0,  0],
       [ 0, 10,  0],
       [ 0,  3,  6]])
       
 3. Algorithm runs in 220 epochs with softmax activation function and batch size is 7 optimizer is adam in one hidden layer the output's are accuracy is
 1 and the loss is 0.00
  classification report
              precision    recall  f1-score   support

           0       1.00      1.00      1.00        11
           1       1.00      1.00      1.00        13
           2       1.00      1.00      1.00         6

    accuracy                           1.00        30
   macro avg       1.00      1.00      1.00        30
weighted avg       1.00      1.00      1.00        30

confution matrix

array([[11,  0,  0],
       [ 0, 13,  0],
       [ 0,  0,  6]])
       
 And the plots are such as 1.train accuracy vs test accuracy, 2.train loss vs test loss and 3.epochs vs loss function are shown in the code.


 
