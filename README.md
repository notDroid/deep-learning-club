# Deep Learning Club
CHS deep learning club tutorials, projects, competitions.

## Tutorial 1: Credit Fraud Classification
![image](https://github.com/notDroid/deep-learning-club/assets/127229451/9d92780d-2bd9-4b32-ad73-61dd72e39f1d) <br> <br>
kaggle notebook: https://www.kaggle.com/code/notdroid/tutorial-1-credit-fraud-classification <br>
kaggle dataset: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud <br>
associated post: https://www.notion.so/Neural-Network-Basics-45d093b62f034260b34e6d098dac014d

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

## Tutorial 2: Rain Prediction
![image](https://github.com/notDroid/deep-learning-club/assets/127229451/4ddbed86-cbf8-42f8-8fb4-e5d8addea8ea)
kaggle notebook: https://www.kaggle.com/code/notdroid/tutorial-2-rain-prediction <br>
kaggle dataset: https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package <br>
associated post: [https://www.notion.so/Deep-Dive-into-Deep-Learning-2b64f8a2e5774e78a4030262775860af](https://evanescent-moon-786.notion.site/Deep-Dive-into-Deep-Learning-2b64f8a2e5774e78a4030262775860af?pvs=4)

1. more in depth data preproccessing with pandas <br>
  a. data imputing <br>
  b. one hot encoding <br>
  c. input normalization
2. addressing the bias-variance tradeoff <br>
  a. split data into training and validation <br>
  b. balance regularization
3. use cosine annealing with linear warmup
4. plot training curves and iterate to find the best model

## Tutorial 3: Digit Recognizer
![image](https://github.com/notDroid/deep-learning-club/assets/127229451/e20fe3f7-b4b4-465c-909b-bf79f2e1c8c6)
kaggle notebook: https://www.kaggle.com/code/notdroid/tutorial-3-digit-recognizer
kaggle dataset: https://www.kaggle.com/competitions/digit-recognizer/data
associated post: https://evanescent-moon-786.notion.site/Convolutional-Neural-Networks-ebf47cf0add046a092a85ef616ad52af?pvs=4
