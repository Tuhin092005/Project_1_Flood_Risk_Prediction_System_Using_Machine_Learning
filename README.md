# 🌊 Flood Risk Prediction System

Predicting flood occurrence using Machine Learning algorithms based on environmental and geographical factors.

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikitlearn)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-purple?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-blue?logo=numpy)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 📌 Project Overview

Floods are among the most destructive natural disasters, causing significant damage to human life, infrastructure, and the environment.

This project uses **Machine Learning** techniques to predict whether a flood is likely to occur based on various environmental and geographical parameters. Three different classification algorithms are implemented and compared to identify the best-performing model.

---

## 🎯 Objectives

- Predict flood occurrence using historical environmental data.
- Compare the performance of multiple Machine Learning models.
- Identify the most accurate prediction model.
- Build a simple and efficient flood prediction system.

---

## 📂 Dataset Features

The dataset contains the following features:

- 📍 Latitude
- 📍 Longitude
- 🌧 Rainfall (mm)
- 🌡 Temperature (°C)
- 💧 Humidity (%)
- 🌊 River Discharge (m³/s)
- 📈 Water Level (m)
- ⛰ Elevation (m)
- 🌿 Land Cover
- 🌱 Soil Type
- 👥 Population Density
- 🏗 Infrastructure
- 📚 Historical Floods

### Target Variable

- **Flood Occurred**
  - `0` → Low Flood Risk
  - `1` → High Flood Risk

---

## 🛠 Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## 🤖 Machine Learning Models

The following models are implemented:

- Logistic Regression Classifier
- Decision Tree Classifier
- Random Forest Classifier

---

## ⚙ Project Workflow

```
Dataset
    │
    ▼
Data Preprocessing
    │
    ▼
Encoding Categorical Data
    │
    ▼
Train-Test Split
    │
    ▼
Model Training
    │
    ▼
Prediction
    │
    ▼
Performance Evaluation
```

---

## 📊 Model Performance

| Model | Accuracy |
|--------|----------|
| Logistic Regression | **90.15%** |
| Decision Tree Classifier | **99.40%** |
| Random Forest Classifier | **99.55%** |

> **Best Performing Model:** Logistic Regression Classifier

---

## 📁 Project Structure

```
Project_1_Flood_Risk_Prediction_System_Using_Machine_Learning/
│
├── Flood_Risk_Prediction_System.ipynb
├── Flood_Risk_Prediction_System.py
├── Dataset/
│   ├── flood_risk_india.csv
├── images/
│   ├── confusion_matrix.png
│   ├── feature_importance.png
│   └── model_accuracy_comparison.png
├── best_model.pkl
├── feature_names.pkl 
├── label_encoders.pkl
├── scaler.pkl 
├── requirements.txt
├── README.md
└── LICENSE
```

---

## 🚀 Installation

### Clone the repository

```bash
git clone https://github.com/Tuhin092005/Project_1_Flood_Risk_Prediction_System_Using_Machine_Learning.git
```

### Navigate to the project

```bash
cd Project_1_Flood_Risk_Prediction_System_Using_Machine_Learning
```

### Install required libraries

```bash
pip install -r requirements.txt
```

### ▶️ Run the project

### Using Python

```bash
python Flood_Risk_Prediction_System.py
```

### Using Google Colab Using Python

Open

```text
Flood_Risk_Prediction_System.ipynb
```

Upload:

- flood_risk_india.csv

Run all cells.

---

## 📈 Sample Predictions

The model predicts flood risk using two different input scenarios.

### 🧪 Example Prediction 1 (High Flood Risk)

**Input**

```text
Latitude             : 22.57
Longitude            : 88.36
Rainfall             : 250 mm
Temperature          : 30°C
Humidity             : 85%
River Discharge      : 500 m³/s
Water Level          : 8 m
Elevation            : 10 m
Land Cover           : 2
Soil Type            : 1
Population Density   : 5000
Infrastructure       : 1
Historical Floods    : 3
```

**Expected Output**

```text
Prediction : 1

Flood Risk : HIGH
```

> A location with heavy rainfall, high humidity, high water level, and multiple historical floods is predicted as **High Flood Risk**.

---

### 🧪 Example Prediction 2 (Low Flood Risk)

**Input**

```text
Latitude             : 23.50
Longitude            : 87.50
Rainfall             : 40 mm
Temperature          : 28°C
Humidity             : 55%
River Discharge      : 80 m³/s
Water Level          : 2 m
Elevation            : 120 m
Land Cover           : 1
Soil Type            : 2
Population Density   : 300
Infrastructure       : 3
Historical Floods    : 0
```

**Expected Output**

```text
Prediction : 0

Flood Risk : LOW
```

> A location with low rainfall, lower humidity, higher elevation, and no historical floods is predicted as **Low Flood Risk**.

---

## 📌 Future Improvements

- Hyperparameter tuning
- Cross-validation
- Feature importance analysis
- Interactive web application using Streamlit or Flask
- Real-time weather API integration
- Interactive dashboard for visualization

---

## 👨‍💻 Author

**Tuhin Maji**

B.Tech in Computer Science & Engineering (AI & ML)

Meghnad Saha Institute of Technology (MSIT), Kolkata

---

## ⭐ If you found this project useful

Give this repository a ⭐ and feel free to fork it!

---

## 📜 License

This project is intended for educational and learning purposes.

---

## ⭐ Support

If you like this project,

⭐ Star this repository

🍴 Fork this repository

📢 Share it with others

Happy Coding! 🚀
