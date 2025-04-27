
# 📊 Applied ML Projects — Financial Forecasting & Customer Risk Prediction

Welcome to a curated portfolio of cutting-edge Machine Learning applications, designed to address real-world problems in **time-series forecasting** and **customer risk prediction**. These projects incorporate state-of-the-art models, precise performance evaluations, and practical business impact, making them ideal for **Applied Scientist** roles at top-tier companies (MAANG+).

---

## 🚀 Project Highlights

### 💳 **1.Customer Transaction Prediction with XGBoost**  


**Objective:** Predict whether a customer will make a transaction based on anonymized tabular data — a high-stakes, imbalanced binary classification problem critical to financial decision systems.

- **Model:** Gradient Boosted Decision Trees using optimized **XGBoost**.
- **Techniques Used:**  
  - Handled class imbalance using **stratified splitting** and **confusion matrix analysis**.  
  - Extensive **hyperparameter tuning** (max_depth, eta, gamma) with **early stopping** and **tree pruning** for optimal performance.  
  - Employed **cross-validation** to enhance model generalization and prevent overfitting.
  
- **Results:**  
  - 🧠 **Accuracy:** **85%** on the hold-out test set  
  - 🔍 **Recall:** **95%** for the majority class (non-target), **56%** for the target class  
  - 📊 **Precision:** **78%** for the minority (target) class  
  - ⚖️ Achieved a **balanced F1-score** of **65%** for the rare class

- **Business Impact:**  
  - Early **risk detection** and **personalized customer targeting** for financial service platforms.
  - High recall for the non-target class ensures model stability, while precision for the target class aids in **fraud detection** and **customer retention** strategies.

---

### 2. 🧠 **Tesla Stock Forecasting with Multi-Step Stacked LSTM**  


- **Problem:** Traditional stock models struggle to capture long-term temporal dependencies and multivariate correlations in financial data.
- **Solution:** Designed a **multi-step stacked LSTM** model to predict Tesla's Open/Close stock prices using historical OHLCV data.
- **Techniques:**
  - Sequence-to-one LSTM pipeline to predict multi-step future values.
  - Data preprocessing: MinMax normalization, sliding window frame, and rolling forecast evaluation.
- **Results:**  
  - **RMSE:** Approx **3.84 (Open)** and **4.28 (Close)** across multiple forecasting horizons.
  - **Key Insights:** High temporal consistency and low forecast variance even for longer-term predictions.
- **Impact:** This model is suitable for integrating into financial analysis tools, empowering investors with more reliable market predictions.

---

## 🧠 Why These Projects Stand Out

- 🎯 **Real-World Problem Solving:** Focused on high-stakes, business-critical tasks like financial forecasting and fraud detection, providing solutions aligned with market needs.
- 📊 **Performance-Focused Evaluation:** Emphasized key metrics like RMSE for regression tasks and recall for classification, ensuring practical performance.
- 🔄 **End-to-End Pipelines:** Fully integrated processes, from data preprocessing to model deployment, ensuring efficient and scalable solutions.
- 🛠️ **Production-Ready Models:** Designed models for easy transition into production environments, including support for **ONNX** model export for deployment.

---

## 🛠️ Tech Stack

| Category             | Tools & Frameworks                                           |
|----------------------|--------------------------------------------------------------|
| **Languages**         | Python, NumPy, Pandas                                        |
| **Deep Learning**     | Keras, TensorFlow (LSTM)                                     |
| **ML Models**         | XGBoost, Scikit-learn                                        |
| **Visualization**     | SHAP, Matplotlib, Seaborn                                    |
| **Platforms**         | Kaggle, Jupyter Notebook                                     |

---

## 📁 Repository Structure

```
.
├── tesla_stacked_lstm_forecasting.ipynb  # Tesla Stock Forecasting Model
├── xgboost-santander-customer-transaction-prediction.ipynb  # Santander Customer Transaction Prediction
├── assets/                               # Contains all visualizations and supplementary files
│   └── visualizations/                  # Plots and graphs for results
├── README.md                            # Project overview and details
└── requirements.txt                     # Dependencies for running the notebooks
```

---

## 📣 About the Author

**Kheer Sagar Patel**  
🎓 M.Tech in AI & ML, IIITDM Jabalpur  
📌 Passionate about solving **real-world problems** using **scalable ML systems** across various domains, including finance, healthcare, and e-commerce.  

---

#### 🌟 Let’s Connect:

If you’re interested in a **deep dive** into any of these projects or want to explore additional ML solutions, feel free to reach out. I’d be happy to collaborate or provide insights!

---

