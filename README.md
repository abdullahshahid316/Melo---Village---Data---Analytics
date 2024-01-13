Melo Village Data Analytics
Project Overview

This project involves the development of a machine learning model to predict scores for villages based on user actions over time. The data encompasses user interactions and their types, with a focus on how these interactions contribute to an overall score for each village.

Data

The data is sourced from three CSV files: actions.csv, users.csv, and villages.csv.
actions.csv contains user actions with timestamps.
users.csv includes details of each user.
villages.csv lists various villages and their features.
Features

Data Reading: Data from CSV files is read into Python using pandas.
Data Merging: User data is merged with action data for comprehensive analysis.
Visualizations:
Content Type Over Time: Stacked bar charts showing the distribution of content types over time.
User Kind Interactions: Visual representation of user interactions, categorized by user type.
Village Features: Bar charts displaying the number of villages with specific features.
Score Calculation:
Village Score Calculation: A function to compute scores for villages based on visited actions and their types.
User Score Calculation: A similar approach is used to calculate scores for individual users or user groups within a village.
Predictive Modeling:
Using a Linear Regression model to predict village scores based on the timeline of actions.
Tools and Libraries Used

Python Libraries: pandas, matplotlib, numpy, sklearn.
Machine Learning: Linear Regression from sklearn for predictive modeling.
Instructions for Running the Code

Import Libraries: Ensure all required libraries (pandas, matplotlib, numpy, sklearn) are installed.
Load Data: Read the CSV files using pandas.
Execute Functions for Visualizations and Score Calculations: Call the provided functions with the necessary parameters.
Run the Predictive Model: Use the Linear Regression model to predict village scores and visualize the results.
Results

Visualizations: Provided insights into content types, user interactions, and village features.
Score Calculation: Successfully calculated scores for villages and users.
Model Performance: The Linear Regression model provided a baseline for predicting village scores, with metrics like Mean Squared Error (MSE) and Coefficient of Determination (R^2).
Conclusions and Future Work

The project demonstrates the potential of machine learning in analyzing user actions and predicting scores for villages.
Future work could explore more complex models and include additional features for a more accurate prediction.
