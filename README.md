# spotify_songs_regression

# 🎵 Spotify Data Analysis and Prediction

This project involves exploratory data analysis and prediction modeling on a Spotify dataset. The aim is to gain insights into music characteristics and predict the popularity of tracks using various machine learning models.

---

## 📁 Dataset

The dataset includes several musical and audio features such as:
- `track_name`, `artist_name`
- `popularity`
- `danceability`, `energy`, `acousticness`, `instrumentalness`, `valence`, `tempo`, etc.

> Dataset source: Spotify music tracks and features dataset (CSV file)

---

## 🎯 Objectives

- Perform data cleaning and preprocessing
- Explore audio features and their distributions
- Visualize patterns across different artists/tracks
- Predict the popularity of a song using regression models

---

## 🛠️ Technologies Used

- Python 3.x
- pandas, numpy
- matplotlib, seaborn
- scikit-learn
- Jupyter Notebook

---

## 🧠 Workflow Overview

1. **Data Cleaning**
   - Handling missing values
   - Removing duplicates
   - Encoding categorical features if needed

2. **Exploratory Data Analysis (EDA)**
   - Distributions of audio features
   - Correlation heatmap
   - Artist-wise track count, popularity distribution

3. **Feature Engineering**
   - Selecting useful predictors
   - Normalizing numerical values if required

4. **Model Building**
   - Train-test split
   - Models used:
     - Linear Regression
     - Random Forest Regressor
     - Support Vector Regressor (SVR)
     - XGBoost Regressor

5. **Model Evaluation**
   - Metrics: R² Score, MAE, RMSE
   - Model comparison
