# Neural Network models for SIR and SEIR models 
Guide: Dr. Adway mitra (Assistant Professor, Centre of Excellence in Artificial Intelligence, IIT Kharagpur)<br />
  Generated data of susceptible, infected, recovered cases using the **SIR** model for 100 days for 1000 different sets of parameters (beta
  and gamma) by using suitable initial conditions.
 Trained **Neural network model** using Keras to predict susceptible, infected, and recovered data for the next day using values of the previous day [click here to see the notebook](https://github.com/dharma610/Project/blob/master/part1_without_beta.ipynb). Notice the changes when we did the same think but using parameters as one of the feature [click here to see the notebook](https://github.com/dharma610/Project/blob/master/part2_including_beta.ipynb). Got validation accuracy of 0.98937 and test accuracy of 0.9880 for the model
 

  In the next part I trained XGBoost Regression model to predict parameters (beta and gamma) separately one at a time [click here to see the notebook](https://github.com/dharma610/Project/blob/master/part2_Xgboost_beta_pred.ipynb). For beta prediction, got **R2 score
  for training set as 0.99 and on the test as 0.91** and approximately similar results for gamma prediction.
  Extended the above tasks for the **SEIR model** a more complex form of the SIR model involving more parameters compared to the SIR
  model. Got approximately similar results as we got in case of SIR model.
 
