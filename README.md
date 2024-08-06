This project focuses on building an Artificial Neural Network (ANN) to predict customer churn. Utilizing a dataset with various customer attributes, the ANN is trained to determine the likelihood of a customer leaving the bank.

**Workflow** 
Importing Libraries: Necessary libraries such as NumPy, Pandas, TensorFlow, and Keras are imported.
Data Preprocessing: The dataset is loaded, and data preprocessing steps include handling categorical data, label encoding, one-hot encoding, splitting the dataset, and feature scaling. 
Building the ANN: A Sequential model is created using TensorFlow and Keras.
The model architecture consists of an input layer, two hidden layers with ReLU activation, and an output layer with sigmoid activation. Training the ANN: The model is compiled using the Adam optimizer and binary crossentropy loss. It is then trained on the training set for 100 epochs. Making Predictions and Evaluating the Model: Predictions are made on the test set, and the model's performance is evaluated using a confusion matrix and accuracy score.

**Results**
Accuracy: The trained model achieves an accuracy of approximately 86.3% on the test set.

