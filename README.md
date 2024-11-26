# Crop-Recommender-System

### Overview

This project leverages a dataset that combines soil properties, climate, and rainfall data to recommend crops. Using a Random Forest Classifier, the system achieves high accuracy in predicting suitable crops based on soil and environmental parameters.

### Dataset

The dataset used for this project contains the following features:

- N: Ratio of Nitrogen content in the soil
- P: Ratio of Phosphorus content in the soil
- K: Ratio of Potassium content in the soil
- Temperature: Temperature in degrees Celsius
- Humidity: Relative humidity in %
- pH: pH value of the soil
- Rainfall: Rainfall in mm
- Label: The crop type

The dataset includes 2,200 samples with no missing values.

### Methodology

Exploratory Data Analysis (EDA):
- Descriptive statistics
- Correlation analysis
- Pair plots and heatmaps to visualize data relationships

Model Training:
- Preprocessed features and target variable
- Trained a Random Forest Classifier
- Achieved 99% accuracy

### Key Results

- Classification Report: The Random Forest model achieved a weighted average F1-score of 0.99, demonstrating excellent performance.
- Feature Importance: The analysis revealed that Nitrogen (N), pH, and rainfall were the most influential features in determining crop recommendations.

### Streamlit Application

A Streamlit web app has been developed to interact with the model. Users can input the soil and climate parameters to get real-time crop recommendations.

### Source

https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset
