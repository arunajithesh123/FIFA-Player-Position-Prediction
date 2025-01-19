# FIFA-Player-Position-Prediction

## Overview

This project predicts a soccer player's position (Forward, Midfielder, or Defender) using machine learning. The model is trained on FIFA game datasets spanning from FIFA 15 to FIFA 23 and leverages player attributes such as physical, mental, and skill-based measures. The system integrates a Flask-based web app and an Android UI to provide real-time predictions.

## Features

#### Big Data Processing:
Utilizes PySpark to handle extensive datasets efficiently.

#### Machine Learning Model: 
Implements a Random Forest classifier with feature engineering and class balancing techniques.

#### Web-Based Deployment: 
Flask-based web application allows real-time predictions.

#### Android Integration: 
An Android app UI enables predictions directly from mobile.

## Technologies Used

#### Machine Learning: 
Python, PySpark, Random Forest Classifier

#### Backend: 
Flask

#### Frontend: 
Android (Java/Kotlin), HTML/CSS for web

#### Database: 
Firebase/SQLite (Optional for future enhancements)

#### Deployment: 
Google Cloud / Heroku

## Dataset

#### Source: FIFA 15 to FIFA 23 dataset

## Key Features Used:

#### Physical: Pace, Strength, Stamina

#### Technical: Passing, Shooting, Dribbling

#### Mental: Vision, Composure, Positioning

#### Defensive: Tackling, Marking

## Installation & Setup

### 1. Web Application

Prerequisites

Python 3.7+

Flask

PySpark



### 2. Android Application

Prerequisites

Android Studio

Java/Kotlin

Steps

Open android_app/ in Android Studio.

Build and run the application on an emulator or physical device.

The app fetches player attributes and predicts positions via the Flask API.

##  Model Training & Evaluation

#### Data Processing: PySpark for feature engineering

#### Model: Random Forest (with hyperparameter tuning)

#### Performance Metrics:

Accuracy: 82%

Precision: 86%

Recall: 88%

F1-Score: 81%

Confusion Matrix Analysis for better class balance

API Endpoints (Flask)

Method

Endpoint

Description

POST

/predict

Predicts a player's position based on attributes

GET

/status

Checks API health status

Screenshots

Web App



Android App



##  Future Improvements

Deploy the model on Firebase ML Kit for seamless Android integration.

Enhance model using deep learning techniques (e.g., LSTMs, CNNs).

Incorporate real-world player performance data for better generalization.

#### Contributors

Aruna Jithesh (GitHub)


License

MIT License - Free to use and modify!

