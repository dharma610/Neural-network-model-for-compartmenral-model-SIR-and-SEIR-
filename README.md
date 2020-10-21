# Neural Network models for SIR and SEIR models Jun'20 - present
• Generated data of susceptible, infected, recovered cases using the SIR model for 100 days for 1000 different sets of parameters (beta
  and gamma) by using suitable initial conditions.
• Trained Neural network using Keras to predict susceptible, infected, and recovered data for the next day using values of the previous day.
• Trained XGBoost Regression model to predict parameters (beta and gamma) separately one at a time.
• Got validation accuracy of 0.98937 and test accuracy of 0.9880 for the neural network model. And, for beta prediction, got R2 score
  for training set as 0.99 and on the test as 0.91 and approximately similar results for gamma prediction.
• Extended the above tasks for the SEIR model a more complex form of the SIR model involving more parameters compared to the SIR
  model. Got approximately similar results as we got in case of SIR model.
• Training the LSTM model using Keras to generate a time series sequence by using the first few data of a time series of susceptible,
  infected, and recovered data.
