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

## 3. DOTA Winner Prediction
In this challenge, we had to predict the winner from 2 teams in a game of DOTA 2 (A famous Multiple Online Battle Arena (MOBA) game). The details of both the teams are provided. The dataset consists of thousands of games played in the past along with their corresponding winners. Supervised Learning is used to fit the model. 

More information regarding the game can be found at "https://en.wikipedia.org/wiki/Dota_2"

### Back End 
Logistic Regression (sklearn classifier) is used to construct a model that can fit the data. The data is preprocessed to match the requirements of the classifier. A testing accuracy of 60% is achieved. This could further be improved by using a neural network instead of just an sklearn classifier. Also the winner depends upon how the players play and coordinate amongst themselves. 

## Prerequisites
The following need to be preinstalled:

1. Python 3.0 +
2. Jupyter Notebook
