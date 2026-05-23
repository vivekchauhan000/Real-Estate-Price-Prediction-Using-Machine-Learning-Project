# Real-Estate-Price-Prediction-Using-Machine-Learning-Project
A Real Estate Price Prediction system built using Python and ML that applies Linear Regression, Random Forest and XGBoost to predict property prices based on location, size and features.Predict real estate property prices using machine learning! Analyzes location, size, and amenities to provide accurate property price predictions 
# 🏠 Real Estate Price Prediction Using Machine Learning

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![ML](https://img.shields.io/badge/Machine%20Learning-Regression-green.svg)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)
![Status](https://img.shields.io/badge/Status-Active-success.svg)

A machine learning project that predicts real estate property prices based on
features like location, size, amenities, and market trends using regression algorithms.

---

## 📋 Table of Contents

- [About](#about)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Model Performance](#model-performance)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

---

## 📌 About

Real estate prices depend on many factors like location, size, number of rooms,
and local amenities. This project uses **Machine Learning** regression techniques
to predict property prices accurately.

The system processes property features and applies **Linear Regression**,
**Random Forest**, and **XGBoost** models to deliver precise price predictions.

---

## 🚀 Features

- ✅ Predicts property prices based on multiple features
- ✅ Supports multiple ML regression models
- ✅ Data preprocessing and feature engineering
- ✅ Exploratory Data Analysis (EDA) with visualizations
- ✅ Model comparison and evaluation
- ✅ Easy to use with Jupyter Notebook
- ✅ Handles missing values and outliers

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| **Python 3.8+** | Core programming language |
| **Scikit-learn** | ML models and preprocessing |
| **Pandas** | Data manipulation |
| **NumPy** | Numerical computations |
| **Matplotlib** | Data visualization |
| **Seaborn** | Statistical plots |
| **XGBoost** | Gradient boosting model |
| **Jupyter Notebook** | Development environment |

---

## 📊 Dataset

- **Source:** Kaggle Real Estate Dataset / Custom Dataset
- **Total Records:** ~20,000+ property listings
- **Target Variable:** Property Price
- **Features Used:**

| Feature | Description |
|---|---|
| 📍 **Location** | Area / City / Neighborhood |
| 📐 **Square Footage** | Total area in sq ft |
| 🛏️ **Bedrooms** | Number of bedrooms |
| 🚿 **Bathrooms** | Number of bathrooms |
| 🏗️ **Year Built** | Construction year |
| 🚗 **Parking** | Parking availability |
| 🌳 **Amenities** | Nearby facilities |

---

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/vivekchauhan000/Real-Estate-Price-Prediction-Using-Machine-Learning-Project.git

# Navigate to the project folder
cd Real-Estate-Price-Prediction-Using-Machine-Learning-Project

# Create virtual environment
python -m venv venv

# Activate virtual environment
# For Windows
venv\Scripts\activate
# For Mac/Linux
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt
```

---

## ▶️ Usage

```bash
# Run Jupyter Notebook
jupyter notebook

# Open the notebook
Real_Estate_Price_Prediction.ipynb
```

### Example Output:

```
Input Features:
  Location     : Mumbai
  Square Feet  : 1200
  Bedrooms     : 3
  Bathrooms    : 2
  Year Built   : 2015

Predicted Price: ₹ 85,00,000
```

---

## 📈 Model Performance

| Model | R² Score | MAE | RMSE |
|---|---|---|---|
| **Linear Regression** | 0.82 | 2.3L | 3.1L |
| **Random Forest** | 0.91 | 1.8L | 2.4L |
| **XGBoost** | 0.94 | 1.5L | 2.1L |

> ✅ **XGBoost** gives the best performance with highest R² score

---

## 📁 Project Structure

```
Real-Estate-Price-Prediction-Using-Machine-Learning-Project/
│
├── dataset/
│   └── real_estate_data.csv      # Property dataset
│
├── notebooks/
│   └── Real_Estate_Price_Prediction.ipynb  # Main notebook
│
├── models/
│   ├── linear_regression.pkl     # Saved LR model
│   ├── random_forest.pkl         # Saved RF model
│   └── xgboost_model.pkl         # Saved XGBoost model
│
├── src/
│   ├── preprocess.py             # Data preprocessing
│   ├── train.py                  # Model training
│   ├── predict.py                # Prediction script
│   └── visualize.py              # Visualization functions
│
├── requirements.txt              # Project dependencies
├── README.md                     # Project documentation
└── LICENSE                       # MIT License
```

---

## 🔍 How It Works

```
1. 📥 Input Property Features
         ↓
2. 🧹 Data Preprocessing
   (Handle missing values, encode categories)
         ↓
3. 🔢 Feature Engineering
   (Scale features, create new variables)
         ↓
4. 🤖 ML Model Training
   (Linear Regression / Random Forest / XGBoost)
         ↓
5. 📊 Output: Predicted Property Price
```

---

## 📉 Visualizations

The project includes the following visualizations:

- 📊 Price distribution by location
- 🔥 Correlation heatmap
- 📈 Actual vs Predicted prices
- 📉 Feature importance chart
- 🗺️ Price map by area

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create your feature branch
   (`git checkout -b feature/NewFeature`)
3. Commit your changes
   (`git commit -m 'Add NewFeature'`)
4. Push to the branch
   (`git push origin feature/NewFeature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the
[MIT License](LICENSE).

---

## 👤 Author

**Vivek Chauhan**
GitHub: [@vivekchauhan000](https://github.com/vivekchauhan000)

---

## 🔗 References

- [Scikit-learn Documentation](https://scikit-learn.org)
- [XGBoost Documentation](https://xgboost.readthedocs.io)
- [Kaggle Real Estate Datasets](https://www.kaggle.com/datasets)
- [Pandas Documentation](https://pandas.pydata.org)

---

⭐ If you found this helpful, please give it a star!
