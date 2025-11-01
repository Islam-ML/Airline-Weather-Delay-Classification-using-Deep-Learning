
# ✈️ Airline Delay Cause Classification

This project aims to build a **deep learning model** that predicts whether a flight will experience a significant **weather delay (more than 100 minutes)**.  
4	+
The dataset contains multiple delay-related attributes, and the model is implemented using **TensorFlow** and **Keras** in **Google Colab**.
5	+
6	+
---
7	+
8	+
## 📊 Dataset
9	+
10	+
**Dataset Used:** `Airline_Delay_Cause.csv`
11	+
12	+
- Columns such as `carrier`, `airport`, and other identifiers were dropped to focus on numerical features related to delay causes.
13	+
- Missing values were removed to ensure data integrity.
14	+
15	+
---
16	+
17	+
## 🧠 Model Architecture
18	+
19	+
The neural network consists of multiple **Dense** layers with a combination of `tanh` and `sigmoid` activations to capture non-linear relationships in the data.
20	+
21	+
**Details:**
22	+
23	+
- **Optimizer:** Adam (with weight decay)
24	+
- **Loss Function:** Binary Crossentropy
25	+
- **Metric:** Accuracy
26	+
- **Regularization:** EarlyStopping to prevent overfitting
27	+
28	+
---
29	+
30	+
## ⚙️ Training Details
31	+
32	+
| Parameter              | Value         |
33	+
| ---------------------- | ------------- |
34	+
| Training/Testing Split | 75% / 25%     |
35	+
| Batch Size             | 10,000        |
36	+
| Epochs                 | 100           |
37	+
| Metric                 | Accuracy      |
38	+
| Early Stopping         | Patience = 10 |
39	+
40	+
---
41	+
42	+
## 📈 Results
43	+
44	+
- Model achieved **99.76% accuracy** on validation data.
45	+
- Evaluation includes:
46	+
  - Confusion Matrix
47	+
  - Classification Report
48	+
- Visualization done using **Matplotlib** and **Seaborn**.
49	+
50	+
---
51	+
52	+
## 🛠️ Technologies Used
53	+
54	+
- **Python**
55	+
- **Pandas, NumPy**
56	+
- **Matplotlib, Seaborn**
57	+
- **TensorFlow / Keras**
58	+
- **Scikit-learn**
59	+
- **Google Colab**
60	+
61	+
---
62	+
63	+
## 🚀 Future Enhancements
64	+
65	+
- Hyperparameter tuning using **Keras Tuner** or **Optuna**
66	+
- Implement **feature importance analysis**
67	+
- Compare results with classical ML models (e.g., Random Forest, XGBoost)
68	+
- Deploy the model using **Streamlit** or **TensorFlow Serving**
69	+
70	+
---
71	+
72	+
## 👤 Author
73	+
74	+
**Author:** [Your Name]  
75	+
**Date:** November 2025  
76	+
**Repository:** [https://github.com/YourUsername/Airline-Delay-Classification](https://github.com/Islam-ML/Airline-Weather-Delay-Classification-using-Deep-Learning)

---
