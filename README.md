# 💳 Credit Card Fraud Transaction Prediction

This project focuses on building a machine learning pipeline to **detect fraudulent credit card transactions** with high accuracy and minimal false positives. It uses supervised learning models, robust evaluation metrics, and is production-ready with a **Streamlit interface** for real-time prediction.

---

## 🚀 Features

- 🧠 **Machine Learning Models**: Implements Logistic Regression, Random Forest, and XGBoost classifiers.
- 🔍 **Imbalanced Data Handling**: Utilizes techniques like **SMOTE** and **undersampling** to deal with class imbalance.
- 📊 **Evaluation Metrics**: AUC-ROC, Precision-Recall AUC, Brier Score, and Calibration Curves to ensure trustworthy predictions.
- 📈 **Feature Engineering**: Scales numerical features and handles categorical variables.
- ⚙️ **Streamlit App**: Interactive frontend for real-time fraud detection.
- 📦 **Modular Codebase**: Well-structured for easy modification and reuse.

---

## 🗃️ Dataset

- **Source**: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud)
- **Size**: 284,807 transactions, with only 492 frauds (highly imbalanced)
- **Features**: 30 anonymized features including `V1` to `V28`, `Amount`, and `Time`

---

## 🏗️ Project Structure

📁 credit-card-fraud-detection/
│
├── data/ # Raw and processed data
├── models/ # Saved model files (e.g., .pkl)
├── notebooks/ # EDA and development notebooks
├── src/ # Core Python scripts
│ ├── data_preprocessing.py
│ ├── model_training.py
│ ├── evaluation.py
│ └── inference.py
├── app/ # Streamlit app
│ └── app.py
├── Dockerfile # For containerization
├── requirements.txt
└── README.md

yaml
Copy
Edit

---

## 🧪 Evaluation Metrics

- ✅ **Accuracy**
- 🔁 **Precision & Recall**
- 📉 **ROC-AUC & PR-AUC**
- 🧪 **Confusion Matrix**
- 📊 **Calibration Curves**
- 🧮 **Brier Score Loss**

---

## 🖥️ How to Run

### 1️⃣ Install Dependencies

```bash
pip install -r requirements.txt
2️⃣ Run the Streamlit App
bash
Copy
Edit
streamlit run app/app.py
🧑‍💻 Author
Deepak Mandloi
Data Science Enthusiast | LinkedIn | deepakmandloi1706@gmail.com
