# Air Quality Prediction System using Machine Learning

## Overview
This project is an end-to-end Machine Learning system developed to predict Air Quality Index (AQI) categories using pollutant concentration and meteorological data. The system analyzes environmental features and classifies air quality into categories such as Good, Satisfactory, Moderate, Poor, Very Poor, and Severe.

---

# Project Phases

## Phase 1: Data Collection and Preprocessing

In this phase, the air quality dataset containing pollutant concentration and meteorological data was collected and prepared for analysis and model training.

### Data Collection
- Selected an air quality dataset containing:
  - PM2.5
  - PM10
  - NO₂
  - SO₂
  - CO
  - O₃
  - AQI values
  - City and Date information

### Data Preprocessing
- Handled missing values using mean imputation
- Removed records with missing AQI category and date values
- Converted date column into datetime format
- Removed unnecessary columns

### Data Transformation
- Extracted features from date column:
  - Year
  - Month
  - Day
  - Day of Week
- Applied one-hot encoding for city feature
- Applied label encoding for AQI categories
- Saved cleaned dataset for further processing

---

## Phase 2: Exploratory Data Analysis and Feature Engineering

In this phase, exploratory data analysis and feature engineering techniques were performed to understand the dataset and improve model performance.

### Exploratory Data Analysis
- Generated correlation heatmaps
- Visualized AQI category distribution using count plots
- Analyzed relationships between features

### Feature Engineering
- Performed feature extraction from date-time values
- Prepared final dataset for training
- Standardized features using `StandardScaler`

### Tools and Libraries Used
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## Phase 3: Model Training and Evaluation

In this phase, multiple Machine Learning classification models were trained using the preprocessed dataset to predict AQI categories.

### Models Used
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)

### Steps Performed
- Split dataset into training and testing sets
- Applied feature scaling
- Trained classification models
- Generated predictions on test data
- Compared model performances

### Evaluation Metrics
- Accuracy Score
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report
- ROC Curve

---

# Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

# Conclusion
This project demonstrates a complete Machine Learning pipeline for predicting air quality categories using environmental and meteorological data. Multiple classification algorithms were implemented and evaluated to identify the best-performing model for AQI prediction.
