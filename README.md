# 🏏 World T20 Score Predictor Using ML

A Machine Learning-powered web application that predicts the final score of a T20 cricket innings based on the current match situation.

## 🚀 Project Overview

This project uses historical T20 international cricket match data and an XGBoost Regression model to estimate the final score of the batting team.

Users can select:

* Batting Team
* Bowling Team
* Match City
* Current Score
* Overs Completed
* Wickets Fallen
* Runs Scored in Last 5 Overs

The model then predicts the final innings score.

---

## 📊 Features

* Real-time score prediction
* Streamlit-based interactive UI
* XGBoost Regression Model
* Feature Engineering from ball-by-ball cricket data
* Supports major international T20 teams
* Fast and lightweight deployment

---

## 🛠️ Tech Stack

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Scikit-Learn
* XGBoost
* Streamlit
* PyYAML

### Machine Learning

* Regression Model
* Feature Engineering
* One-Hot Encoding
* Standard Scaling
* XGBoost Regressor

---

## 📂 Project Structure

World-T20-Score-Predictor/

├── app.py

├── data_extraction.py

├── feature_extraction.py

├── pipe.pkl

├── requirements.txt

├── README.md

├── .gitignore

└── data/ (ignored)

---

## ⚙️ Installation

Clone the repository:

git clone https://github.com/YOUR_USERNAME/World-T20-Score-Predictor.git

Navigate to the project:

cd World-T20-Score-Predictor

Install dependencies:

pip install -r requirements.txt

Run the application:

streamlit run app.py

---

## 📈 Model Inputs

The prediction model uses:

* Batting Team
* Bowling Team
* City
* Current Score
* Balls Left
* Wickets Left
* Current Run Rate (CRR)
* Runs Scored in Last 5 Overs

---

## 🎯 Model Performance

Algorithm Used:

* XGBoost Regressor

Evaluation Metrics:

* R² Score
* Mean Absolute Error (MAE)

---

## Future Improvements

* IPL Match Support
* Live Match API Integration
* Win Probability Prediction
* Player Performance Analytics
* Docker Deployment

---

## 👨‍💻 Author

Bipin Yadav

Python Backend Developer | FastAPI Developer | SQL | AI & Machine Learning Enthusiast

LinkedIn: Your LinkedIn URL

GitHub: Your GitHub URL
