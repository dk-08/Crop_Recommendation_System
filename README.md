# 🌱🌾 Crop Recommendation System – A Mini Project Using Machine Learning and Flask


This mini-project implements a Crop Recommendation System that leverages machine learning and web development tools to assist farmers or agriculturalists in identifying the most suitable crop to grow based on soil and environmental conditions.


## 📌 Project Overview

This web application uses a trained **Random Forest** classifier to recommend crops based on user-provided values for:
- Nitrogen (N)
- Phosphorus (P)
- Potassium (K)
- Temperature (°C)
- Humidity (%)
- pH (0–14)
- Rainfall (mm)

It provides a simple, user-friendly interface built using **Flask**, allowing users to input parameters and receive crop recommendations instantly.


## 🗃️ Dataset

The dataset used is from **Kaggle**:  
[Crop Recommendation Dataset](https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset)

This dataset contains historical data of crop-growing conditions and their ideal environments.


## ⚙️ Tech Stack
- **Python**
- **Flask** (for the web framework)
- **scikit-learn** (for machine learning)
- **Joblib** (for model serialization)
- **HTML/CSS** (for UI templates)


## 🧠 ML Algorithm


- **Random Forest Classifier**  
Chosen for its high accuracy, ability to handle multivariate input, and robustness to overfitting.


✅ Input Validation
To ensure meaningful predictions:

pH must be between 0 and 14.

Temperature must be below 100°C.

Humidity must be greater than 0%.


✨ Features
Predicts the best crop to grow based on user inputs.

Input validation for realistic and meaningful values.

User-friendly web interface using HTML/CSS templates.

Fast and accurate predictions using Random Forest.


📜 License
This project is open-source and available under the MIT License.


🙌 Acknowledgments
Dataset by Atharva Ingle on Kaggle

(https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset)
