# L2-regularized Linear Regression via Stochastic Gradient Descent

Trained a 2-layer neural network (i.e., linear regression) for age regression
The training data was split 80:20 for training and validation. The hyperparameters and optimized weights are then evaluated on the network on the test set. 

The training and testing data are available here:

•https://s3.amazonaws.com/jrwprojects/age_regression_Xtr.npy

•https://s3.amazonaws.com/jrwprojects/age_regression_ytr.npy

•https://s3.amazonaws.com/jrwprojects/age_regression_Xte.npy

•https://s3.amazonaws.com/jrwprojects/age_regression_yte.npy

Used stochastic gradient descent (SGD). The following hyperparameters were choosen:

•Mini-batch size  ̃n.

•Learning rate ε.

•Number of epochs.

•L2 Regularization strength α.

Following results were obtained:

![image](https://user-images.githubusercontent.com/64325043/223870513-7813df4a-996b-4fa5-b639-295a247d7b51.png)
