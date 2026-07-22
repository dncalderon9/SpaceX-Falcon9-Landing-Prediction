# 🚀 SpaceX Falcon 9 First Stage Landing Prediction

## 📖 Project Overview

This project was developed as the final capstone of the **IBM Applied Data Science Professional Certificate**.

The objective of this project is to predict whether the Falcon 9 first stage booster will successfully land using historical SpaceX launch data. The project combines data collection, data wrangling, exploratory data analysis, interactive visualizations, and machine learning techniques to identify the factors that influence landing success.

---

## 🎯 Project Objectives

- Collect launch data from the SpaceX REST API and Wikipedia.
- Clean and prepare the dataset for analysis.
- Perform Exploratory Data Analysis (EDA).
- Analyze launch data using SQL queries.
- Create interactive visualizations using Plotly Dash and Folium.
- Train and evaluate multiple machine learning classification models.
- Predict Falcon 9 first stage landing success.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Plotly Express
- Dash
- Folium
- BeautifulSoup
- SQLite
- Scikit-learn
- GridSearchCV

---

## 📂 Repository Structure

```
SpaceX-Falcon9-Landing-Prediction
│
├── notebooks
│   ├── 01_Data_Collection_API.ipynb
│   ├── 02_Web_Scraping.ipynb
│   ├── 03_Data_Wrangling.ipynb
│   ├── 04_EDA_Visualization.ipynb
│   ├── 05_EDA_SQL.ipynb
│   ├── 06_Folium.ipynb
│   └── 07_Machine_Learning.ipynb
│
├── dashboard
│   └── spacex_dash_app.py
│
├── presentation
│   └── SpaceX_Capstone_Presentation.pdf
│
├── images
│
└── README.md
```

---

## 📊 Project Workflow

1. Data Collection
   - SpaceX REST API
   - Wikipedia Web Scraping

2. Data Wrangling
   - Handle missing values
   - Feature engineering
   - Data cleaning

3. Exploratory Data Analysis
   - Data visualization
   - SQL analysis
   - Interactive charts

4. Interactive Visual Analytics
   - Folium Maps
   - Plotly Dash Dashboard

5. Predictive Analysis
   - Feature Engineering
   - Data Standardization
   - Model Training
   - Hyperparameter Tuning
   - Model Evaluation

---

## 🤖 Machine Learning Models

The following supervised learning models were trained and optimized using GridSearchCV:

- K-Nearest Neighbors (KNN)
- Decision Tree
- Logistic Regression
- Support Vector Machine (SVM)

---

## 📈 Results

- Historical launch data was successfully collected, cleaned, and analyzed.
- Interactive dashboards and maps were developed for visual exploration.
- Four classification models were trained and evaluated.
- All models achieved approximately **83.3% accuracy** on the test dataset.
- Although SVM obtained the highest cross-validation score, all models produced identical predictions on the unseen test set, demonstrating consistent predictive performance.

---

## 🚀 Future Improvements

- Incorporate additional launch features.
- Experiment with ensemble learning techniques such as Random Forest and XGBoost.
- Deploy the predictive model as a web application.
- Continuously update the model with future SpaceX launch data.

---

## 👨‍💻 Author

**Nelson Calderon**

Industrial Engineer | Data Analytics | Machine Learning | Python | SQL

---

## 📄 License

This project was developed for educational purposes as part of the IBM Applied Data Science Professional Certificate.
