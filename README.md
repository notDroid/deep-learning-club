# deep-learning-club
CHS deep learning club tutorials, projects, competitions

## Tutorial 1: Credit Fraud Classification
![image](https://github.com/notDroid/deep-learning-club/assets/127229451/9d92780d-2bd9-4b32-ad73-61dd72e39f1d)
1. basic data manipulation with pandas .iloc[row index, column index]
2. creating a classificaiton model <br>
  a. using a better activation function relu with he uniform initialization <br>
  b. adding more layers and units to increase complexity <br>
  c. using step decay during training
3. addresssing class imbalance <br>
  a. using class weights to weight positive and negative cases equally in the loss function <br>
  b. using AUC metric to get a reliable metric for performance
4. evaluating the model <br>
  a. using the F1 score to find the best threshold and get the best metric for final model performance

Applied Knowledge:
1. Need for complexity <br>
  a. Activation Functions <br>
  b. More layers mean more layers of complexity (nuerual network is a big composite function)
2. Measuring performance <br>
  a.  Loss function
3. Gradient Descent <br>
  a. To improve the network learn the optimal values for the parameters W,b <br>
  b. Use information about the derivatives (gradient) to update values <br>
  c. Learning rate impacts convergence
4. Training <br>
  a. Forward propagate: compute output and loss <br>
  b. Back propagate: compute gradient <br>
  c. Update parameters <br>
  d. go to next batch (cycle through dataset)
