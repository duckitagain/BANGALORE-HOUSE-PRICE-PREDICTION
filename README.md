# 🏠 Bangalore House Price Prediction

A Machine Learning project that predicts house prices in Bangalore using property features such as location, square footage, number of bedrooms, and bathrooms. The project demonstrates a complete end-to-end machine learning workflow, from data preprocessing and feature engineering to model training and prediction.

---

## 📌 Overview

Bangalore's real estate market is complex, with prices varying significantly across different locations and property types. This project aims to build a regression model capable of estimating house prices based on key property attributes.

The project focuses on practical machine learning techniques used in real-world predictive analytics, including data cleaning, outlier handling, categorical encoding, and model evaluation.

---

## 🚀 Features

* Cleaned and preprocessed a real-world housing dataset.
* Handled missing values and inconsistent records.
* Removed outliers to improve model performance.
* Performed feature engineering for better predictions.
* Encoded categorical variables using One-Hot Encoding.
* Trained and evaluated regression models using Scikit-learn.
* Predicted house prices for new property inputs.

---

## 🛠️ Tech Stack

* **Python**
* **Pandas**
* **NumPy**
* **Scikit-learn**
* **Matplotlib**
* **Jupyter Notebook**

---

## 📂 Project Structure

```text
BANGALORE-HOUSE-PRICE-PREDICTION/
│
├── data/
├── notebooks/
├── model/
├── app.py
├── requirements.txt
└── README.md
```

---

## ⚙️ Machine Learning Pipeline

1. Load the Bangalore housing dataset.
2. Clean and preprocess the data.
3. Handle missing values.
4. Remove outliers.
5. Perform feature engineering.
6. Encode categorical features.
7. Split the dataset into training and testing sets.
8. Train regression models.
9. Evaluate model performance.
10. Predict prices for unseen properties.

---

## 📊 Input Features

| Feature    | Description           |
| ---------- | --------------------- |
| Location   | Area within Bangalore |
| Total Sqft | Total property area   |
| BHK        | Number of bedrooms    |
| Bathrooms  | Number of bathrooms   |
| Balcony    | Number of balconies   |

**Target Variable:** House Price

---

## 📈 Example Prediction

| Property                      | Predicted Price |
| ----------------------------- | --------------- |
| 2 BHK, 1200 sqft, Whitefield  | ₹75 Lakhs       |
| 3 BHK, 1800 sqft, Indiranagar | ₹1.45 Crore     |

*The above values are sample predictions for demonstration purposes.*

---

## 💻 Installation

Clone the repository:

```bash
git clone https://github.com/duckitagain/BANGALORE-HOUSE-PRICE-PREDICTION.git
```

Move into the project directory:

```bash
cd BANGALORE-HOUSE-PRICE-PREDICTION
```

Install the required packages:

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Project

Run the application:

```bash
python app.py
```

Or open the notebook:

```bash
jupyter notebook
```

---

## 📌 Future Improvements

* Deploy the model using Streamlit.
* Implement XGBoost for improved accuracy.
* Add hyperparameter tuning.
* Build an interactive web interface.
* Create a REST API for predictions.

---

## 🎯 Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Regression Modeling
* Model Evaluation
* Python Programming
* Git & GitHub

---

## 👨‍💻 Author

**Gourav Rajak**

B.Tech – Artificial Intelligence & Machine Learning

GitHub: **duckitagain**

If you found this project useful, consider giving it a ⭐ on GitHub.
