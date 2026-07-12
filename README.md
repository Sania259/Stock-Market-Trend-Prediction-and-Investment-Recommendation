# 📈 Stock Market Trend Prediction and Investment Recommendation using Deep Learning

A deep learning-based framework for **stock market trend prediction and investment recommendation** using historical stock data of top NIFTY companies. This project leverages **LSTM**, **GRU**, and **Explainable AI (SHAP)** to predict stock trends and provide interpretable investment recommendations.

---

## 🚀 Project Overview

Predicting stock market movements is a challenging task due to the highly dynamic and nonlinear nature of financial markets. This project develops and evaluates multiple deep learning architectures for stock trend prediction and combines them with Explainable AI techniques to improve transparency and decision-making.

The project consists of:

- Data preprocessing and feature engineering
- Stock trend prediction using LSTM and GRU models
- Performance evaluation of multiple model architectures
- Investment recommendation based on predicted returns
- Explainability using SHAP

---

## ✨ Features

- Historical stock market data preprocessing
- Multiple LSTM and GRU architectures
- Multi-stock prediction framework
- Investment recommendation module
- Explainable AI using SHAP
- Performance evaluation using regression metrics

---

## 🛠 Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Scikit-learn
- SHAP
- Matplotlib
- Plotly
- TA (Technical Analysis Library)
- Jupyter Notebook

---

## 📂 Repository Structure

```
Stock-Market-Trend-Prediction-and-Investment-Recommendation
│
├── notebooks/
│
├── images/
│
├── requirements.txt
│
└── README.md
```

---

## 📊 Dataset

This project uses historical stock market data of top NIFTY companies.

**Note:** The dataset is **not included** in this repository due to GitHub file size limitations.

---

## 🧠 Model Architecture

The project explores multiple deep learning architectures including:

- LSTM (3 variants)
- GRU (2 variants - Independent and Dependent)

The Dependent Multi-Stock GRU model achieved the best overall performance.

---

## 📈 Performance

### Best Performing Model

**Dependent Multi-Stock GRU**

| Metric | Value |
|---------|--------|
| RMSE | 126.68 |
| MAE | 92.92 |

The model was evaluated on historical stock data and demonstrated strong predictive capability for financial time-series forecasting.

---

## 📸 Project Screenshots

### System Architecture

![Architecture](images/System_Architecture.png)

### Prediction Results

![Prediction](images/prediction_results.png)

### SHAP Explainability

![SHAP](images/SHAP_plot.png)

---

## ⚙ Installation

Clone the repository

```bash
git clone https://github.com/Sania259/Stock-Market-Trend-Prediction-and-Investment-Recommendation.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

1. Install the required libraries.
2. Place the dataset inside the project directory.
3. Open the notebooks.
4. Execute the notebooks sequentially.

---

## 🔮 Future Improvements

- Transformer-based architectures
- Real-time stock prediction
- News sentiment analysis
- Portfolio optimization
- Streamlit web application
- Deployment on cloud

---

## 🏆 Research Recognition

This project formed the basis of our research paper:

**"Stock Trend Prediction and Recommendation Using LSTM and GRU with Explainable AI."**

🏅 **Best Paper Award – ICETEST 2026**

---

## 👩‍💻 Author

**Sania Narendra Ayare**

Bachelor of Engineering (Information Technology)

Interested in Machine Learning, Deep Learning, Data Science, and AI-powered Financial Analytics.

---

## ⭐ If you found this project useful, consider giving it a star!
