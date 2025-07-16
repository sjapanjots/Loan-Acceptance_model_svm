# 🏦 Loan Acceptance Prediction using SVM

A machine learning application that predicts whether a loan application will be accepted or rejected using a **Support Vector Machine (SVM)** classifier and a simple web interface built with **Streamlit**.

---

## 🚀 Project Overview

This project aims to help financial institutions or loan officers assess loan eligibility based on applicant information. A Support Vector Machine model is trained on historical loan data to perform binary classification: **Accepted** or **Rejected**.

---

## 💻 Tech Stack

- **Python**
- **scikit-learn** – For model training and SVM implementation
- **Streamlit** – For building the user-friendly web app
- **Pandas / NumPy** – For data manipulation
- **Pickle** – To serialize the trained SVM model

---

## 📄 What's Inside

- `loan_model.pkl`  
  Trained SVM model stored using Pickle.

- `app.py`  
  Streamlit web application file where the model is used for real-time prediction.

- `requirements.txt`  
  Python dependencies required to run the app:
  ```
  streamlit
  scikit-learn
  pandas
  numpy
  ```

---

## 🧠 How It Works

1. Users input key loan-related features:
   - Credit score
   - Income
   - Loan amount
   - Employment type
   - Marital status
   - And other relevant financial features

2. The input is passed to the trained SVM model.

3. Output:
   - **1** → Loan Approved  
   - **0** → Loan Rejected

---

## 📦 How to Run Locally

1. **Clone the repository**:
   ```bash
   git clone https://github.com/sjapanjots/Loan-Acceptance_model_svm.git
   cd Loan-Acceptance_model_svm
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Streamlit app**:
   ```bash
   streamlit run app.py
   ```

4. Visit `http://localhost:8501` in your browser.

---

## ✅ Example Usage

- **Input**:  
  - Credit Score: 750  
  - Income: ₹50000  
  - Loan Amount: ₹200000  
  - Employment Type: Salaried  

- **Output**:  
  ✅ **Loan Approved**

---

## 🙋‍♂️ Author

**Japanjot Singh**  
Data Scientist & ML Enthusiast  
📬 sjapanjots@gmail.com