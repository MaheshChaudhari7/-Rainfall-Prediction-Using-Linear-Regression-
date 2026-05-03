# 🌧️ Rainfall Prediction Using Linear Regression

![Python](https://img.shields.io/badge/Python-3.12-blue?style=for-the-badge&logo=python)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

> A Machine Learning web application that predicts rainfall (in mm) based on climate parameters like temperature, humidity, and wind speed across major Indian states.

---

## 📌 Project Overview

This project uses **Linear Regression** to predict rainfall for different Indian states based on:
- Average Temperature
- Humidity
- Wind Speed
- State & Month

The app is built with **Streamlit** for an interactive and user-friendly interface.

---

## 🚀 Features

- 📊 View synthetic India climate dataset
- 🗺️ Select from 5 major Indian states
- 📅 Choose any month of the year
- 🌡️ Adjust temperature, humidity, and wind speed
- 🤖 Get instant ML-based rainfall prediction

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Python 3.12 | Core language |
| Streamlit | Web UI framework |
| Scikit-Learn | ML model (Linear Regression) |
| Pandas | Data processing |

---

## 📁 Project Structure

```
RainfallApp/
├── app.py            # Main Streamlit application
├── requirements.txt  # Python dependencies
├── .gitignore        # Git ignore file
└── README.md         # Project documentation
```

---

## ⚙️ Installation & Setup

**1. Clone the repository**
```bash
git clone https://github.com/MaheshChaudhari7/-Rainfall-Prediction-Using-Linear-Regression-.git
cd -Rainfall-Prediction-Using-Linear-Regression-
```

**2. Create virtual environment**
```bash
python -m venv .venv
.venv\Scripts\activate
```

**3. Install dependencies**
```bash
pip install -r requirements.txt
```

**4. Run the app**
```bash
streamlit run app.py
```

**5. Open in browser**
```
http://localhost:8501
```

---

## 📸 Screenshots

### Prediction Output
> Select state, month, and climate values → Click **Predict Rainfall** → Get result instantly!

---

## 🌍 States Covered

| State | Rainfall Pattern |
|---|---|
| Maharashtra | Moderate |
| Kerala | High (+40mm) |
| Tamil Nadu | Moderate |
| Rajasthan | Low (-15mm) |
| Punjab | Moderate |

---

## 📊 Dataset Info

- **Type:** Synthetic India Climate Data
- **Records:** 200
- **Features:** State, Month, Temperature, Humidity, Wind Speed
- **Target:** Rainfall (mm)

---

## 🤖 ML Model

- **Algorithm:** Linear Regression
- **Library:** Scikit-Learn
- **Train/Test Split:** 80% / 20%
- **Encoding:** One-Hot Encoding (pd.get_dummies)

---

## 👤 Author

**Maheshh Chaudhari**

[![GitHub](https://img.shields.io/badge/GitHub-MaheshChaudhari7-black?style=flat&logo=github)](https://github.com/MaheshChaudhari7)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
