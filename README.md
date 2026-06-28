# project2

# ❤️ Heart Disease Prediction

## 📌 Project Overview

This project focuses on predicting the presence of heart disease using machine learning techniques. The dataset contains clinical and demographic information collected from patients. The project compares supervised learning models and explores unsupervised learning for data clustering.

---

## 🎯 Objectives

- Predict whether a patient has heart disease.
- Compare the performance of different classification models.
- Explore hidden patterns in the dataset using clustering.
- Visualize the optimal number of clusters with the Elbow Method.

---

## 📂 Dataset

The dataset contains **918 patient records** and **12 features**.

| Feature | Description |
|----------|-------------|
| Age | Age of the patient |
| Sex | Gender (Male/Female) |
| ChestPainType | Type of chest pain |
| RestingBP | Resting blood pressure |
| Cholesterol | Serum cholesterol (mg/dL) |
| FastingBS | Fasting blood sugar |
| RestingECG | Resting electrocardiogram results |
| MaxHR | Maximum heart rate achieved |
| ExerciseAngina | Exercise-induced angina |
| Oldpeak | ST depression induced by exercise |
| ST_Slope | Slope of the peak exercise ST segment |
| HeartDisease | Target variable (0 = No Disease, 1 = Heart Disease) |

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🤖 Machine Learning Models

### Supervised Learning

- Logistic Regression
- Support Vector Machine (SVC)

### Unsupervised Learning

- K-Means Clustering
- Elbow Method (to determine the optimal number of clusters)

---

## 📊 Project Workflow

1. Load the dataset
2. Explore the data
3. Data preprocessing
   - Handle categorical variables
   - Feature scaling
4. Train classification models
5. Evaluate model performance
6. Apply K-Means clustering
7. Plot the Elbow Method

---

## 📈 Evaluation Metrics

The classification models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

---

## 📉 K-Means Clustering

The Elbow Method was used to identify the optimal number of clusters by plotting the Within-Cluster Sum of Squares (WCSS).

---

## 📁 Project Structure

```
HeartDisease/
│
├── HeartDisease.ipynb
├── heart.csv
├── README.md
└── images/
    └── elbow_method.png
```

---

## 🚀 How to Run

1. Clone the repository

```bash
git clone https://github.com/yourusername/HeartDisease.git
```

2. Install dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Run the notebook

```bash
jupyter notebook HeartDisease.ipynb
```

---

## 📌 Future Improvements

- Try additional machine learning algorithms.
- Perform hyperparameter tuning.
- Add cross-validation.
- Build a web application using Streamlit.
- Deploy the model online.

---

## 👤 Author

**Hanan Alshammary**

Master's Student in Data Science

---

## ⭐ If you found this project useful, consider giving it a star!
