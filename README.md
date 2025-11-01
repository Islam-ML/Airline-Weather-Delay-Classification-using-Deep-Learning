
# ✈️ Airline Delay Cause Classification

This project aims to build a **deep learning model** that predicts whether a flight will experience a significant **weather delay (more than 100 minutes)**.  

The dataset contains multiple delay-related attributes, and the model is implemented using **TensorFlow** and **Keras** in **Google Colab**.

---

## 📊 Dataset

**Dataset Used:** `Airline_Delay_Cause.csv`

- Columns such as `carrier`, `airport`, and other identifiers were dropped to focus on numerical features related to delay causes.

- Missing values were removed to ensure data integrity.

---

## 🧠 Model Architecture

The neural network consists of multiple **Dense** layers with a combination of `tanh` and `sigmoid` activations to capture non-linear relationships in the data.

**Details:**

- **Optimizer:** Adam (with weight decay)

- **Loss Function:** Binary Crossentropy

- **Metric:** Accuracy

- **Regularization:** EarlyStopping to prevent overfitting

---

## ⚙️ Training Details

| Parameter              | Value         |

| ---------------------- | ------------- |

| Training/Testing Split | 75% / 25%     |

| Batch Size             | 10,000        |

| Epochs                 | 100           |

| Metric                 | Accuracy      |

| Early Stopping         | Patience = 10 |


---

## 📈 Results

- Model achieved **99.76% accuracy** on validation data.

- Evaluation includes:

  - Confusion Matrix

  - Classification Report

- Visualization done using **Matplotlib** and **Seaborn**.

---

## 🛠️ Technologies Used

- **Python**

- **Pandas, NumPy**

- **Matplotlib, Seaborn**

- **TensorFlow / Keras**

- **Scikit-learn**

- **Google Colab**

---

## 🚀 Future Enhancements

- Hyperparameter tuning using **Keras Tuner** or **Optuna**

- Implement **feature importance analysis**

- Compare results with classical ML models (e.g., Random Forest, XGBoost)

- Deploy the model using **Streamlit** or **TensorFlow Serving**

---

## 👤 Author

**Author:** [Your Name]  

**Date:** November 2025  

**Repository:** [https://github.com/YourUsername/Airline-Delay-Classification](https://github.com/Islam-ML/Airline-Weather-Delay-Classification-using-Deep-Learning)

---
