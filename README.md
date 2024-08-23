
# Airline Passenger Referral Prediction

## Introduction 

Welcome to the Airline Passenger Referral Prediction project! This project aims to analyze airline reviews from 2006 to 2019 to predict whether passengers would recommend an airline to their friends and family. By leveraging machine learning techniques, we strive to identify the key factors that influence customer satisfaction and help airlines improve their services.


## Abstract 

In the competitive airline industry, understanding what drives customer satisfaction is crucial for retaining passengers and attracting new ones. This project focuses on predicting passenger referrals by analyzing a rich dataset of airline reviews collected over 13 years. We use a combination of Exploratory Data Analysis (EDA) and Machine Learning (ML) classification techniques to build models that predict referral likelihood with high accuracy. By identifying the critical aspects of passenger experience, airlines can enhance their services and boost customer loyalty.


## Dataset Information

The dataset used in this project includes airline reviews from 2006 to 2019, covering popular airlines worldwide. The data was scraped in Spring 2019 and consists of both structured responses and free-text comments. Below are the key features in the dataset:

1. Airline: Name of the airline.
2. Overall: Overall rating given to the trip (1 to 10).
3. Author: Name of the review author.
4. Review Date: Date when the review was posted.
5. Aircraft: Type of the aircraft used.
6. Traveler Type: Type of traveler (e.g., Business, Family Leisure, Solo Leisure, Couple Leisure).
7. Flight Date: Date of the flight.
8. Cabin Service: Rating for cabin service (1 to 5).
9. Food & Beverage: Rating for food and beverage quality (1 to 5).
10. Ground Service: Rating for ground service (1 to 5).
11. Value For Money: Rating for value for money (1 to 5).
12. Recommended: Binary label indicating whether the passenger would recommend the airline (target variable).
13. Customer Review: Free-text review provided by the customer.
14. Route: Route taken by the flight.
15. Seat Comfort: Rating for seat comfort.


## Problem Statement

The primary goal of this project is to predict whether a passenger would recommend an airline based on various factors such as overall rating, traveler type, cabin service, food and beverage quality, ground service, and value for money. By building a machine learning model on the airline reviews dataset, we aim to accurately identify the key determinants of customer satisfaction and provide actionable insights for improving airline services. The insights gained from this project can guide airlines in making informed decisions to enhance the overall passenger experience and increase referral rates.


## Conclusion 

In this project, we explored two machine learning models to solve the classification problem:

Logistic Regression Model
Random Forest Model
After preprocessing the data and addressing the class imbalance, we applied these models to predict passenger referrals. The Logistic Regression model achieved an accuracy of 91%, while the Random Forest model initially achieved 90% accuracy. Through Hyperparameter Tuning using GridSearchCV, we optimized the Random Forest model, ultimately reaching the same 91% accuracy.

These models can effectively predict passenger referrals, enabling airlines to identify key customers who can drive revenue growth. To achieve this, airlines must focus on providing excellent cabin service, ground service, food and beverage quality, and seat comfort. These factors are crucial in enhancing passenger satisfaction and fostering positive word-of-mouth referrals.





