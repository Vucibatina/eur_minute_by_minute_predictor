# eur_minute_by_minute_predictor
Recurrent Neural Network to predict minute by minute prices of EUR/USD

Repository contains minute by minute data of EUR/USD for the past 10 years (with the exception of 2014). 

This Notebook will build a RNN Model to predict the movement of the EUR prices based of historical minute by minute data.

Training and testing is easily separated by picking a year for training and another year for testing. This, however, is not a great practice as training and testing sets are not equaly and randomly represented. You will need to change the code to get better representation of training and testing.

For the purposes of playing around, you can play with Hyperparameters to design your model.
