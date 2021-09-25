# Stock-Sentimental-Analysis-Classifier
Classify the stock market with help of news headlines

## Table of Content
  * Demo
  * Overview
  * Motivation
  * Installation and Run 
  * Deployement on Heroku
  * Using Bag of Words to Vectorization
  * Database Link
  * Future scope of project
  


## Linkdin Profile
For any queries regarding about this project contact me

Link : https://www.linkedin.com/in/anil-l-b023631b6/

## Demo
Project output demo Link: [https://stockanalys.herokuapp.com/]

## Data Collection 
Stock sentimental analysis using news headlines dataset Extracted the Dataset from the Kaggle you can also extract the data from this link https://www.kaggle.com/yash612/stockmarket-sentiment-dataset , Kaggle is an Open source and have a large community also they conduct competitions every month,Kaggle allows users to find and publish data sets, explore and build models in a web-based data-science environment, work with other data scientists and machine learning engineers, and enter competitions to solve data science challenges,
Given the thousands of other people also doing them, it is becoming harder and harder for merely working through them to be enough to differentiate you. You'll learn a lot, but it won't make you stand out from your competition.Data scientists of all levels can benefit from the resources and community on Kaggle. Whether you are a beginner, looking to learn new skills and contribute to projects, an advanced data scientist looking for competitions, or somewhere in between, Kaggle is a good place to learn

## Screenshots


![Screenshot 2021-09-23 at 8 31 20 PM](https://user-images.githubusercontent.com/71332138/134535597-e985cec4-389e-4918-b9d2-39dfb72b4b4e.png)

-------------------------------------------------------------------------------------------------------------------------------------------------------------


![Screenshot 2021-09-23 at 8 32 20 PM](https://user-images.githubusercontent.com/71332138/134535617-452acd23-450b-4cd4-8ecd-d8a00ea4cbdf.png)

-------------------------------------------------------------------------------------------------------------------------------------------------------------

![Screenshot 2021-09-23 at 8 31 35 PM](https://user-images.githubusercontent.com/71332138/134536215-7bc2750d-0803-4d43-8c6c-cdc69c49e590.png)





## Overview
The markets reflect rational behavior or human irrationality? Mass psychology's effects may not be the only factor driving the markets, but it’s unquestionably significant.
This fascinating quality is something that we can measure and use to predict market movement with surprising accuracy levels.
With the real-time information available to us on massive information in newspaper like Times of Inadia and Deccan Haeralad, we have all the data we could ever need to create these predictions.
But then comes the question, how can our computer understand what this unstructured text data means?
That is where sentiment analysis comes in. Sentiment analysis is a particularly interesting branch of Natural Language Processing (NLP), which is used to rate the language used in a body of text.
Through sentiment analysis, we can take thousands of tweets about a company and judge whether they are generally positive or negative (the sentiment) in real-time!
Developed these POC for to get experience real time projects and Created API using Streamlit Framework and Deployed to the Heroku Cloud platform

## Motivation
What to do when you are at home due to this pandemic situation? I started to learn Machine Learning model to get most out of it. I came to know mathematics behind all supervised models and unspurervised models. Finally it is important to work on application (real world application) to actually make a difference. To get a experience you have to work thats the reason to perform my favourable work done.

## Installation and Run
The Code is written in Python 3.9 If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:

     Step 1: pip install -r requirements.txt
     
     Step 2: Streamlit run app.py

## Deployement on Heroku
Login or signup in order to create virtual app. You can either connect your github profile or download ctl to manually deploy this project.

[![](https://i.imgur.com/dKmlpqX.png)](https://heroku.com)

## Using Bag of Words to Vectorization

Text data is used in natural language processing (NLP), which interacts between humans and machines using natural language. Text data helps analyze movie reviews, products using Amazon reviews, etc. But the question that arises here is how to deal with text data when building a machine learning model?
Text data is converted to a real-valued vector by various techniques. One such approach is Bag of Words (BoW), which will be discussed in this article. But why do we have to convert the text into a vector? Why can’t we use text data to build a machine learning model?
Need for text vectorization
Let’s say we have reviews of a product. Text reviews provided by the customers are of different lengths. By converting from text to numbers, we can represent a review by a finite length of the vector. In this way, the length of the vector will be equal for each review, irrespective of the text length.
Bag of words is the most trivial representation of text into vectors. Each column of a vector represents a word. The values in each cell of a row show the number of occurrences of a word in a sentence.

To Know more about vectorization click here : 

[https://towardsdatascience.com/text-vectorization-bag-of-words-bow-441d1bfce897]


## Technologies Used

![](https://forthebadge.com/images/badges/made-with-python.svg)  ![pandas](https://user-images.githubusercontent.com/71332138/134156736-9dcc4675-e588-42a6-9481-816ac08654ab.png). ![nltk](https://user-images.githubusercontent.com/71332138/134540164-b00fafda-ccde-49ce-a5c5-3019a856f860.png) 

![blog sklearn](https://user-images.githubusercontent.com/71332138/134540412-a009eb7d-f4fa-412f-bc1a-a5c89ba74aa4.png). ![numpy](https://user-images.githubusercontent.com/71332138/134540645-95fa9566-18ca-4719-8cc6-82153e96683c.png) 
                               ![streamlit](https://user-images.githubusercontent.com/71332138/134540838-49dda9c6-3cf8-4695-be7b-5af1aff6e394.png)


## Database Link : 
[https://www.kaggle.com/yash612/stockmarket-sentiment-dataset]


## Future Scope

* Optimize Streamlit app.py
* Add extra Features
* Develop Front-End 
