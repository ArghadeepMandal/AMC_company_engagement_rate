# AMC_company_engagement_rate

## Overview
This repository contains code for predicting engagement scores of videos on an online content sharing platform. The engagement score is assigned based on user interaction with the videos, such as likes, comments, and shares. Predicting engagement scores helps improve user interaction and identifies content that appeals to a larger audience.
## Problem Statement
ABC is an online platform where users can create, upload, and share videos. The goal is to develop a machine learning approach to predict the engagement score of a video on a user level.
## Dataset
### Train Data
- **row_id:** Unique identifier of the row
- **user_id:** Unique identifier of the user
- **category_id:** Category of the video
- **video_id:** Unique identifier of the video
- **age:** Age of the user
- **gender:** Gender of the user (Male and Female)
- **profession:** Profession of the user (Student, Working Professional, Other)
- **followers:** No. of users following a particular category
- **views:** Total views of the videos present in the particular category
- **engagement_score:** Engagement score of the video for a user
### Test Data
- Similar structure to the train data without the engagement_score
## Table of Contents
1. **Importing the Relevant Libraries**
2. **Data Inspection**
3. **Data Cleaning**
4. **Exploratory Data Analysis**
5. **Building Model**
## Code Overview
### Data Inspection
- Loaded train and test datasets.
- Checked shape and null value ratios.
- Explored data types, categorical, and numerical features.
### Exploratory Data Analysis (EDA)
- Visualized categorical features.
- Examined distribution plots for various numerical features.
- Treated outliers.
### Building Model
- Label-encoded categorical features.
- Split data into features (X) and target (y).
- Used Linear Regression model.
- Evaluated the model using Root Mean Squared Error.
## Model Evaluation
- Utilized a Linear Regression model.
- Calculated and visualized correlation matrix.
- Plotted count distribution for different features.
- Generated bar plots to show the relationship between profession and engagement_score.
## Submission
- Created a submission file.
- Made predictions using the trained model on the test set.
- Ensured only positive predictions for the target variable.
## Conclusion
This project focuses on predicting engagement scores using a machine learning model, providing insights into user interactions and preferences on the ABC content sharing platform.
Feel free to explore the code and adapt it to your specific needs.
