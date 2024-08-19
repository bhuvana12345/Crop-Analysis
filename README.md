# Global Crop Yield Prediction and Recommendation System

## Project Overview
This project focuses on predicting crop yields and providing recommendations for agricultural practices across the world. By leveraging data science and machine learning techniques, we aim to empower stakeholders in the agricultural sector with insights for informed decision-making and sustainable farming practices.

## Table of Contents
1. [Technologies Used](#technologies-used)
2. [Data Sources](#data-sources)
3. [Project Workflow](#project-workflow)
4. [Machine Learning Models](#machine-learning-models)
5. [Crop Recommendation System](#crop-recommendation-system)
6. [Power BI Dashboard](#power-bi-dashboard)
7. [Installation and Usage](#installation-and-usage)
8. [Future Work](#future-work)
9. [Contributors](#contributors)
10. [License](#license)

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow/Keras
- Power BI

## Data Sources
The project utilizes datasets from [Our World in Data](https://ourworldindata.org/agricultural-production), including information on:
- Fertilizer usage
- Pesticide use
- Water resources
- Historical crop yields for various staple crops

## Project Workflow
1. **Data Collection and Merging**: 
   - Imported multiple CSV files
   - Merged datasets based on common columns (Entity, Code, Year)

2. **Data Cleaning and Preprocessing**:
   - Handled missing values
   - Removed irrelevant data (e.g., 'World' data)
   - Renamed columns for clarity

3. **Exploratory Data Analysis (EDA)**:
   - Generated summary statistics
   - Created visualizations (histograms, heatmaps, scatter plots)
   - Analyzed correlations between variables

4. **Feature Engineering**:
   - Applied scaling techniques (Min-Max scaling, Z-score standardization)

5. **Model Development and Evaluation**:
   - Implemented various machine learning models
   - Evaluated models using appropriate metrics

6. **Crop Recommendation System**:
   - Developed a system to recommend crops based on input features

7. **Power BI Dashboard Creation**:
   - Designed an interactive dashboard for data visualization and insights

## Machine Learning Models
1. **Multiple Linear Regression**:
   - Used to predict crop yields based on the year

2. **Logistic Regression**:
   - Applied for binary classification of crop yields
   - ROC curve analysis for model evaluation

3. **K-Nearest Neighbors (KNN)**:
   - Implemented for regression on multiple crop yields

4. **Decision Tree Regression**:
   - Used for predicting wheat yield

5. **Random Forest Regression**:
   - Applied for wheat yield prediction and feature importance analysis

6. **Long Short-Term Memory (LSTM) Neural Network**:
   - Utilized for time series forecasting of wheat yield

## Crop Recommendation System
- Developed using Random Forest Classifier
- Recommends the highest-yielding crop based on input features:
  - Fertilizer quantity
  - Nitrogen content
  - Potash content
  - Phosphate content
  - Pesticide usage
  - Water resources

## Power BI Dashboard
- Created an interactive dashboard featuring:
  - Visualizations of key agricultural trends
  - Crop yield predictions
  - Comparative analysis of different crops and regions
  - User-friendly interface for exploring data

## Installation and Usage
[Provide instructions on how to set up the project, install dependencies, and run the code]

## Future Work
- Incorporate more recent data and expand the geographical scope
- Explore advanced machine learning techniques like deep learning for improved predictions
- Integrate real-time data sources for more dynamic recommendations
- Enhance the Power BI dashboard with additional interactive features

