![alt text](https://www.callcentrehelper.com/images/stories/2018/03/chatbot-at-desk-messaging-760.png)

# AI CHATBOT

## Table of content
  * [Overview]
  * [Motivation]
  * [Installation]
  * [Project Details]
  * [Technologies used]
  
## Overview
Just like Google assistant, Apple's Siri, Microsoft's Cortona, Amazon's Alexa this chatbot also works like the same but with a limitation and that is it has limited pattern and response. If we add more pattern and response, it can response to all our queries.

## Motivation
Getting instant reply in chatbox of some organization, made me always think whether there is a person active all the time or is there some technology behind this. Then i came to know about the term "Chatbot" and after that i became interested in knowing how a chatbot works, what is the mechanism behind the idea. Now, after having knowledge on Python, Machine learning and Deep Learning, i finally understood the basic concept, and therefore, thought of creating my own simple chatbot.  

## Installation
The code is written in Python 3.7 in Jupyter Notebook. If you dont have it you can first download Anaconda platform [here](https://docs.anaconda.com/anaconda/install/), where You will find the Jupyter Notebook within it. Jupyter Notebooks are powerful, versatile, shareable and provide the ability to perform data visualization in the same environment.It also allows data scientists to create and share their documents, from codes to full blown reports. They help data scientists streamline their work and enable more productivity and easy collaboration. Due to these and several other reasons you will see below, Jupyter Notebooks are one of the most popular tools among data scientists.

After installing Anaconda, you have to install two packages- 
1. "json" package, to access the json file. You can install the package by simply running the following code in anaconda prompt.
`pip install jsonlib`
2. "keras" library to build the model. For that you have to run the following code in anaconda prompt.
`pip install keras`

## Project Detail
### Workflow of the project:
   * [Create a pattern and response in the Json file.]
   * [Train the model using the json file.]
   * [Create a GUI to interact with the chatbot ]
   
### Create a pattern and response in the Json file.
First i have created a json file using Python IDLE. The file contains all the required patterns and responses along with tags to train our model. Since i am using limited pattern and response, we can also add pattern and response to this file which will increase the response to our queries.
Here, the name of the json file is `info.json`. You can modify this file using Python IDLE according to your need.

### Train the model using the json file.
The first step of creating a chatbot is training the model by using some algorithms. Here we are dealing with the text data and our machine knows only 0's and 1's. For that we need to use the technique called Bag of words to convert the text to numbers. Before using Bag of words we have to preprocess our text data. NLP makes it possible for computers to read text, hear speech, interpret it, measure sentiment and determine which parts are important. 
After creating Bag of words, I took the pattern value as the training input and their classes as the training output data. I used the Convolution Neural Network (CNN) with two hidden layers and 128 neurons in the first layer and 64 neurons in the second layer. Used the dropout operation to make it a sparse network instead of a deep network to avoid the problem of overfitting. Activation function Rectified Linear Unit (ReLU) is used for the neural network and the Softmax function for the output layer and Stochastic Gradient Descent (SGD) optimizer is used instead of gradient descent. I saved the model as `chatbot_model.h5`. You can directly use this model if you want.

## Create a GUI to interact with the chatbot
For user interaction i have created a simple user interface using "tkinter". To know more about tkinter click [here.](https://realpython.com/python-gui-tkinter/) 



## Technologies Used
![](https://keras.io/img/logo-k-keras-wb.png)
![](https://miro.medium.com/max/1000/0*iL0ELUnHdGtN8bkP.png)
![](https://www.innocreate.com/wp-content/uploads/2017/07/jsonlogo-300x300.png)
![](https://bids.berkeley.edu/sites/default/files/styles/400x225/public/projects/numpy_logo_project_page_banner.png?itok=jaJeRlWs)
![](https://i.ytimg.com/vi/oD4IvH-Talo/hqdefault.jpg)
![](https://i2.wp.com/iot4beginners.com/wp-content/uploads/2020/04/65dc5834-de21-4e2e-bd4d-5e0c3c6994dd.jpg?fit=375%2C422&ssl=1)
