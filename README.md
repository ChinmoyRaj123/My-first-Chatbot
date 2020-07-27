![alt text](https://image.shutterstock.com/image-vector/chatbot-concept-virtual-assistance-website-260nw-713628037.jpg)

# IMDB-movie-recommendation

## Table of content
  * [Overview]
  * [Motivation]
  * [Installation]
  * [Project Details]
  * [Technologies used]
  
## Overview
This a simple movie recommendation system trained by K Nearest Neighbors. This model is trained on 1000 movies rated by IMDb, which will use KNN algorithm to recommend five movies simillar to a movie that we like. The movies recommended will be within that 1000 movies but we can expand our choices by adding new data into that list of 1000 movies.

## Motivation
The idea of creating a movie recommendation struck me when i was watching a good IMDb rated movie. I liked that movie so much that i wanted to watch another movie of that same genre. But to search a movie having good rating and same genre in a huge list of IMDb movies was tiresome. Therefore it led me into building this model. 

## Installation
The code is written in Python 3.7 in Jupyter Notebook. If you dont have it you can first download Anaconda platform [here](https://docs.anaconda.com/anaconda/install/), where You will find the Jupyter Notebook within it. Jupyter Notebooks are powerful, versatile, shareable and provide the ability to perform data visualization in the same environment.It also allows data scientists to create and share their documents, from codes to full blown reports. They help data scientists streamline their work and enable more productivity and easy collaboration. Due to these and several other reasons you will see below, Jupyter Notebooks are one of the most popular tools among data scientists.

After installing Anaconda, Run the Jupyter Notebook where you can use the code (`IMDB movie recommendation.ipynb`).

## Project Detail
As you have learned that this project is built on 1000 IMDb rated movies, i have used the csv file `imdb_1000.csv` as my input data which is located in my 'D:' drive. You can change the path of the input file as you like in the code. Here, the input file contains information like Title, Content_rating, Star_rating, Genre, Duration and Actors_list. I have only taken the necessary information in building the model. After my model is built, you can see that it recommended 5 movies based on a movie that i liked.

## Technologies Used
![](https://forthebadge.com/images/badges/made-with-python.svg)
![](https://i.redd.it/c6h7rok9c2v31.jpg)
![](https://twilio-cms-prod.s3.amazonaws.com/original_images/jupyter_python_numpy.png)

