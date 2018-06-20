# sentiment-analysis-on-IMDB-dataset-using-pytorch
Author: Ujjawal Sharma(ujjawalsharma15@gmail.com)
## performance
Test accuracy: 53%
###
For better results use whole dataset ,I have only used 10% of training examples because of computational restrictions
## description
### step 1: 
Loading the test and train data and splitting into train, validation and test folds
### step 2: 
LSTM(bidirectional) used with dropout as regularizer.
### step 3: 
Cross Entropy Loss(binary) used for evaluation
### step 4: 
Training the model on train set and final evaluation on test set.
