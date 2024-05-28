# Advertisement-Click-Prediction

The goal of the project is to learn from the historical data of advertisement clicks using machine learning and create a model to Predict who is going to click on the Advertisement on a website in future based on the user behaviour and user profile.

In below project I will discuss the step by step approach to create a Machine Learning predictive model in such scenarios. You can use this flow as a template to solve any supervised ML classification problem.

The flow of the case study is as below:

* Reading the data in python
* Defining the problem statement
* dentifying the Target variable
* Looking at the distribution of Target variable
* Basic Data exploration
* Rejecting useless columns
* Visual Exploratory Data Analysis for data distribution (Histogram and Barcharts)
* Feature Selection based on data distribution
* Outlier treatment
* Missing Values treatment
* Visual correlation analysis
* Statistical correlation analysis (Feature Selection)
* Converting data to numeric for ML
* Sampling and K-fold cross validation
* Trying multiple classification algorithms
* Selecting the best Model
* Deploying the best model in production
* I know its a long list!! Take a deep breath... and let us get started!

Reading the data into python
This is one of the most important steps in machine learning! You must understand the data and the domain well before trying to apply any machine learning algorithm.

Data Description
This data set contains the following features:

* VistID: The id for the user visit on website
* Time_Spent: Average time spent by user on site in minutes
* Age: User age in years
* Area_Income: Average Income of geographical area of user
* Internet_Usage: Average minutes a day user spent on the internet
* Ad_Topic: Headline of the advertisement
* Country_Name: Country of user
* City_Code: City of user
* Male: Whether or not user was male
* Time_Period: Time at which consumer clicked on Ad
* Weekday: Name of the day
* Month: Name of the months
* Year: Which year the data is collected
* Clicked: 0 means not clicked and 1 means that user clicked the Ad.
* It has one file "Ad click data.csv". This file contains the historical data of various users and different ads which they were exposed to and if they have clicked on the ad or not?

