# KAGGLE COMPETITIONS

Kaggle Competitions is a collection of solutions to various competitions hosted on Kaggle. The following competition were tried:

1. Titanic: ML from disaster
2. Digit Recognizer 
3. DOTA Winner Prediction 

## 1. Titanic: ML from disaster
In this challenge, we had to complete an analysis of what sorts of people were likely to survive in the most infamous shipwreck (the sinking of RMS Titanic). A simple neural network is put to work to predict which passengers survived the tragedy. All the passenger data has been provided.

### Details 
Some feature engineering was employed to gain further insights into the dataset. Some new features such as CallSign, Surname, SameSurname and SameTicket were generated using the original features. 
The complete detail about the competition is provided at "https://www.kaggle.com/c/titanic".

### Back End 
A Neural Network with fully connected single hidden layer is fed the preprocessed data. The model automatically learns the nuances of the data and predicts whether a given person would die in the Titanic disaster or not. 

## 2. Digit Recognizer
In this challenge, we had a task to recognize handwritten digits using the famous MNIST dataset. It is a basic Computer Vision problem where the goal is to correctly identify digits from 0 to 9 from a dataset which includes pre-extracted features.
The complete detail about the competition is provided at "https://www.kaggle.com/c/digit-recognizer".

### Back End 
The features in the data are the corresponding pixel values of the image. The neural network architecture is as follows:

Input Neurons : 784
Weight 1 : (784, 784)
Hidden Neurons : 784
Weight 2 : (1, 784)
Output Neuron : 1

