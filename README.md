Video Game Sales Regional Analysis:

Project Overview

This comprehensive data science project analyzes video game sales patterns across different global regions (North America, Europe, Japan, and Other markets) to identify market opportunities and optimize game development strategies. The analysis leverages machine learning techniques to understand how genre, platform, and publisher influence regional consumer preferences, ultimately helping developers make data-driven decisions to balance their global market presence.

Problem Statement

How can game developers increase video game sales across specific regions to create a more balanced global market by identifying underperforming platforms and genres and implementing data-driven strategies?
Hypothesis

Video game sales by specific region are influenced by genre, platform, and publisher, and aligning these factors with regional preferences will lead to increased sales and a more balanced global market.
Dataset

The project utilizes a comprehensive video game sales dataset containing:

Game titles and release information
Genre classifications
Platform details
Publisher information
Regional sales breakdowns (North America, Europe, Japan, and Other regions)
Global sales figures

Methodology
The project follows a structured data science workflow:
1. Data Preparation and Cleaning

Handling missing values and outliers
Feature engineering including binary classification of sales performance by region
Normalization and standardization of numerical features
One-hot encoding of categorical variables (Genre, Platform, Publisher)

2. Exploratory Data Analysis

Visualization of sales distribution across regions
Analysis of genre popularity by market
Platform performance comparison across regions
Correlation analysis between features and regional sales
Time-based trends in regional preferences

3. Predictive Modeling
The project implements and compares five machine learning models to predict regional sales performance:

Logistic Regression
Support Vector Machine (SVM)
Random Forest Classifier
Multi-Layer Perceptron (MLP) Neural Network
Long Short-Term Memory (LSTM) Neural Network

4. Model Evaluation
Models are rigorously evaluated using multiple metrics:

Accuracy, Precision, Recall, and F1-scores
ROC curves and AUC scores
Confusion matrices
Cross-validation performance
