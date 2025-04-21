# 🌍 QuakeSense: Earthquake Magnitude Prediction Using ML

**QuakeSense** is a machine learning project that predicts earthquake magnitude from geophysical data. The model is trained on a cleaned historical earthquake event dataset and is deployed as an interactive web application using **Streamlit** on **Replit**.

---

## 🚀 Project Highlights

- 📊 Predicts earthquake magnitude from features such as location, depth, and time.
- 🧠 Uses machine learning models (Linear Regression & Random Forest).
- 📁 Cleaned and preprocessed dataset from 18,000+ seismic records.
- ✅ Web app developed using **Streamlit**, deployed on **Replit**.
- 📈 Performance analysis and feature importance study performed.

---



## 📦 Features

- Custom parser for raw, irregular seismic data.
- Extracting features from timestamp data (Year, Month, Day, Hour).
- Model comparison based on performance measures: MAE, MSE, R².
- Visualizing feature importance.
- Real-time prediction web form interactive.

---

## 🧠 Machine Learning Models

| Model              | MAE    | MSE    | R² Score |
|-------------------|--------|--------|----------|
| Linear Regression | 0.318  | 0.181  | 0.007    |
| Random Forest     | 0.312  | 0.173  | 0.049    |

✅ Final model: **Random Forest Regressor**, selected for improved accuracy and feature management.

---

## 📚 Dataset Overview

| Feature   | Description                                     |
|-----------|-------------------------------------------------|
| Latitude  | Epicenter's north–south coordinate              |
| Longitude | Epicenter's east–west coordinate                |
| Depth     | Earthquake depth in kilometers                  |
| Year      | Extracted from timestamp                        |
| Month     | Extracted from timestamp                        |
| Day       | Extracted from timestamp                        |
| Hour      | Extracted from timestamp                        |
| Mag       | Earthquake magnitude (target variable)          |

- 💾 Final training samples: 14,424
- 📊 Test samples: 3,606

---

## 🖥️ Try It Live

This app is built with **Streamlit** and hosted on Replit.

```bash
# Run it locally (or in Replit shell)
streamlit run app.py
```
## 📁 Project Structure

quakesense/

├── app.py                   # Streamlit web app

├── random_forest_model.pkl  # Trained ML model

├── data/                    # Raw and processed datasets

├── visuals/                 # Feature importance plots

├── requirements.txt         # Python dependencies

└── README.md                # Project documentation


## 🛠 Tech Stack

Python 3.10+
pandas, numpy, scikit-learn
joblib (for saving models)
matplotlib, seaborn (for visualization)
Streamlit (for the frontend)
Replit (for web-based deployment)


## 🙋‍♀️ Author
Subhali AR Otti
IIIT Naya Raipur, Chhattisgarh, India
Under the guidance of Prof. Vijaya J


