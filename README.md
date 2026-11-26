# Traffic-Flow-Prediction
Predicting traffic conditions using machine learning by analyzing historical traffic volume, weather data, and time-based patterns.

## Overview

Traffic volume varies depending on several factors, including time of day, weather conditions, holidays, and seasonal patterns. Understanding these variations can help identify recurring traffic trends and classify traffic conditions.

This project analyzes historical traffic volume data and uses machine learning classification algorithms to categorize traffic conditions into **Low, Medium, and High** traffic levels. It also explores the influence of weather conditions and time-based variables on traffic volume.

## Objectives

- Analyze historical traffic volume data.
- Identify traffic patterns across different hours, days, and months.
- Explore the relationship between weather conditions and traffic volume.
- Perform data cleaning and exploratory data analysis.
- Create time-based features from timestamp data.
- Categorize traffic volume into Low, Medium, and High classes.
- Train and compare different machine learning classification models.
- Evaluate model performance using appropriate classification metrics.

## Dataset

**Metro Interstate Traffic Volume Dataset**

The dataset contains historical traffic volume measurements from the westbound lane of Interstate 94 in Minnesota, along with weather-related attributes and timestamp information.

### Dataset Features

| Feature | Description |
|---|---|
| holiday | Holiday information |
| temp | Temperature |
| rain_1h | Rainfall recorded in one hour |
| snow_1h | Snowfall recorded in one hour |
| clouds_all | Cloud coverage |
| weather_main | Main weather condition |
| weather_description | Detailed weather description |
| date_time | Date and time of observation |
| traffic_volume | Recorded traffic volume |

Dataset source: [UCI Machine Learning Repository – Metro Interstate Traffic Volume](https://archive.ics.uci.edu/dataset/492/metro+interstate+traffic+volume)

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## Methodology

### 1. Data Exploration
Examining the dataset structure, statistical summaries, features, and missing values.

### 2. Data Cleaning
Handling missing values, removing duplicate records, and converting timestamp data into the appropriate format.

### 3. Exploratory Data Analysis
Visualizing traffic patterns and analyzing the relationship between traffic volume, time, and weather conditions.

### 4. Feature Engineering
Extracting features such as hour, day, month, year, day of the week, weekends, and holidays from the timestamp and other columns.

### 5. Traffic Categorization
Dividing traffic volume into three categories:
- Low
- Medium
- High

### 6. Data Preprocessing
Applying imputation, feature scaling, and categorical encoding to prepare the dataset for machine learning.

### 7. Model Training
Training multiple classification algorithms on the prepared dataset.

### 8. Model Evaluation
Comparing model performance using different evaluation metrics and visualizations.

## Machine Learning Models

The following classification algorithms are implemented:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

## Evaluation Metrics

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

These metrics are used to compare the models and assess their classification performance.

## Results

The performance of the implemented models is compared to identify the model that provides the best classification results for traffic categories.

The analysis also includes actual versus predicted traffic categories and feature importance to understand the factors influencing the model's predictions.

## Conclusion

This project demonstrates the application of data analysis and machine learning techniques to historical traffic volume data. By analyzing time-based and weather-related features, traffic patterns can be explored and traffic conditions can be classified into different categories.

The comparison of multiple classification models provides insight into their performance and suitability for traffic classification. The project combines data preprocessing, exploratory analysis, feature engineering, model training, and evaluation into a complete machine learning workflow.

## Project Files

- `Traffic_Flow_Prediction.ipynb` – Google Collab Notebook containing the complete implementation of the traffic classification project, including data analysis, feature engineering, machine learning model development, and performance evaluation.
- `Metro_Interstate_Traffic_Volume.csv` – Dataset used for the project.
- `README.md` – Project documentation.
