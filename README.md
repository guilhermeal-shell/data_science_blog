# Writing a Data Science Blog Post
This repository contains one jupyter notebook in which the public-domain Seatle Airbnb Dataset has been analyzed for data interpretation and price modelling using machine learning 

Medium Blog Post
Here you can find blog post on Medium about this project: https://medium.com/@emrebilgehangedik/seattle-airbnb-listings-analysis-d88c839596f8

Project Motivation
This project (Write a Data Science Blog Post) is part of Udacity Data Scientists Nanodegree Program.

I used Seattle Airbnb Dataset for this project. As part of the Airbnb Inside initiative, the dataset describes the listing activities of homestays in Seattle, WA. The orijinal dataset can be found here: https://www.kaggle.com/airbnb/seattle

This project focuses on analyzing this data to answer the following questions:
1) What is the averaged price per accommodate in the different neighbourhoods of the city ?
2) Is there any correlation between the response rate by the host and the price of the accommodation ? The intent here is to identify if there is any trend indicating that relatively cheaper accommodations (i.e. lower price/number of accommodates ratio) eventually have also a lower response rate by the host, in other words, they are more difficult to book.
3) How the 10 most abundant property types are distributted accross the neighbourhoods of Seatle?
4) Which features in the dataset have the higher linear correlation with the price of an accommodation?
5) Can we leverage Machine Learning to predict the price of an accomodation based on the features selected by domain-knowledge?


Libraries
The data was analyzed in Python 3.10, using the following libraries:
- Pandas 2.2.2
- Sci-kit Learn 1.5.1
- Matplotlib 3.9.1


File Descriptions
1) Seattle Airbnb Dataset.ipynb Jupyter notebook with complete analysis, answers to the questions, explanations and visualisations
2) listings.csv Original dataset in csv format
