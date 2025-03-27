# Dissertaion_project
Spotify HIT Prediction, Dissertation project(Machine Learning)
# 🎵 Spotify HIT Prediction Project

## 📌 **Description**
This project aims to predict whether a song will become a hit on Spotify by analyzing its audio features. By leveraging **machine learning models**, the project classifies songs as either hits or non-hits based on characteristics such as **danceability, energy, tempo, loudness**, and more. The goal is to provide insights into the factors influencing a song's popularity and develop a predictive model to anticipate future hits.

---

## 📊 **Dataset Information**
- **Source:** Spotify API / Kaggle dataset
- **Size:** Includes thousands of songs with audio features and hit labels
- **Features:**
    - `danceability`: How suitable a track is for dancing.
    - `energy`: Intensity and activity level of a track.
    - `tempo`: Beats per minute (BPM).
    - `loudness`: Overall volume of the track.
    - `valence`: Positivity or happiness of the track.
    - `duration_ms`: Length of the track in milliseconds.
    - `popularity`: Score from 0 to 100 indicating how popular the song is.
    - `label`: Target variable indicating whether the song is a hit (1) or not (0).

---

## ⚙️ **Technologies Used**
- **Programming Language:** Python
- **Libraries and Frameworks:**
    - `pandas` – for data manipulation
    - `numpy` – for numerical operations
    - `matplotlib` & `seaborn` – for data visualization
    - `scikit-learn` – for machine learning model development
    - `XGBoost` – for improved model performance

---

## 🔥 **Project Workflow**
### 1️⃣ **Data Preprocessing:**
- Imported the dataset and performed **data cleaning**.
- Handled missing values and standardized numerical features.
- Applied **feature scaling** to normalize the data.

### 2️⃣ **Exploratory Data Analysis (EDA):**
- Visualized the distribution of hits vs. non-hits.
- Analyzed the correlation between features using **heatmaps**.
- Plotted key feature distributions such as tempo, energy, and loudness.

### 3️⃣ **Model Development:**
- Splitted the data into **training and testing sets**.
- Utilized multiple machine learning algorithms:
    - **Logistic Regression**: Baseline model.
    - **Random Forest**: Improved accuracy with ensemble learning.
    - **XGBoost**: Final model with the best performance.
- Tuned hyperparameters using **GridSearchCV** for optimization.

### 4️⃣ **Evaluation:**
- Measured model accuracy, precision, recall, and F1-score.
- Visualized the **ROC curve** and AUC to assess model performance.

---

## 📈 **Key Results and Insights**
- **Feature Importance:** Danceability, tempo, and energy had the highest influence on song popularity.
- **Model Performance:** The **XGBoost model** achieved the highest accuracy (~85%) and F1-score, making it the most effective in predicting hit songs.
- **Visualization:** Graphs showcasing the correlation between popularity and key audio features were created.

---

## 📊 **Visualizations and Examples**
Here are some of the key visualizations included in the project:
- **Feature Correlation Heatmap:** Displays the relationship between audio features and popularity.
- **Popularity Distribution:** Shows the distribution of popular vs. non-popular songs.
- **Feature Distribution:** Highlights the tempo, loudness, and energy differences between hits and non-hits.

---

✅ *Feel free to explore and enhance this project!* 🎉


