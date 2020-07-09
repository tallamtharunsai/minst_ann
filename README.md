# minst_ann
Ann using python for digit recognition

Here I have used ANN which have three dence layers goes like this:

model.add(layers.Dense(128, activation='relu', input_shape=(X_train.shape[1],)))

model.add(layers.Dense(128, activation='relu'))

model.add(layers.Dense(10, activation='softmax'))

the number (128 and 10) are the hidden layers' neurons.

the last (10) is the output layer as we have 0-9 digits.

The dataset is from kaggle compititions. You can get the data form the following link:
https://www.kaggle.com/c/digit-recognizer/data
