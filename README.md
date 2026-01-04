# [IBM Data Science - Analyzing SpaceX Rocket Launches]

## Overview
The goal of the project is to simulate the complete data science workflow, using SpaceX launch data to predict if Falcon 9 first stage will land successfully or not

## Data
- Scraped SpaceX API for launch data
- https://api.spacexdata.com/v4/launches/past
- Preprocessing steps: Used pandas and numpy to clean and create a dataframe of Falcon 9 launches with their features and success/failure class column

## Methods
- Performed Data Scraping, Data Wrangling, Data Exploration with SQL, Data Visualization: Interactive Map with Folium and Dashboard with Plotly, and Predictive modeling with SVM, Logistic Regression, and Decision Tree Classifiers
- Libraries: pandas, numpy, seaborn, sqlite3, Folium, Plotly, sklearn

## Results
- Decision Tree Classifier gave best training performance.
- Accuracy of predicting success/failure of launch: 0.8857142857142856
- Note: Following IBM labs, the testing data size was insufficient to get any sort of conclusion. Decided to use training accuracy as my evaluation metric
- Created Powerpoint presentation detailing the entire Data Science process
  

## Key Learnings
- Data Science work is a sequential process, where the next step is entirely dependent on the level of polish of the previous step. It is imperative to make sure the early steps, such as data collection and data wrangling, are near perfect to ensure the predictive modeling steps go smoothly.
- While I was excited to complete this IBM lab and certification, I found the entire program to be fairly basic and easy. I want to explore alternative data exploration methods and predictive modeling methods
