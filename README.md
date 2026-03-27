# 📉 Customer Churn Prediction app

A machine learning web application built with Streamlit that predicts whether a telecom customer will churn or not based on their details.

---

## 🚀 Live Demo
Run locally using Streamlit — see setup instructions below.

---

## 📌 Features
- Predicts customer churn in real-time
- Simple and interactive UI built with Streamlit
- Trained on Telco Customer Churn dataset
- Uses a pre-trained ML model with feature scaling

---

## 🛠️ Tech Stack
- Python
- Streamlit
- Scikit-learn
- NumPy
- Joblib
- Jupyter Notebook (for model training)

---

## 📂 Project Structure
```
Customer_Churn_Analysis/
├── app.py                          # Streamlit web app
├── Customer_Churn_Analysis.ipynb   # Model training notebook
├── model (1).pkl                   # Trained ML model
├── scaler (1).pkl                  # Feature scaler
├── WA_Fn-UseC_-Telco-Customer-Churn.csv  # Dataset
└── README.md                       # Project documentation
```

---

## ⚙️ Setup & Installation

1. **Clone the repository**
```bash
   git clone https://github.com/adityaraj536/Customer_Churn_Analysis.git
   cd Customer_Churn_Analysis
```

2. **Install dependencies**
```bash
   pip install streamlit scikit-learn numpy joblib
```

3. **Run the app**
```bash
   streamlit run app.py
```

---

## 📊 Input Features
| Feature | Description |
|--------|-------------|
| Age | Customer age |
| Gender | Male or Female |
| Tenure | Months with the company |
| Monthly Charge | Monthly billing amount |

---

## 🎯 Output
- **Yes** — Customer is likely to churn ⚠️
- **No** — Customer is likely to stay ✅

---

## 👤 Author
**Aditya Raj**  
GitHub: [@adityaraj536](https://github.com/adityaraj536)

---

## 📃 License
This project is open source and available under the [MIT License](LICENSE).
