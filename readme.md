

# 🚑 Insurance Claim Prediction

A **Machine Learning web application** built with **Streamlit** that predicts whether an insurance claim will be approved or not, based on customer and claim-related data.

🔗 **Live Demo:** [Insurance Claim Prediction App](https://insuranceclaimprediction.streamlit.app/)

---

## 📌 Project Overview

Insurance companies face challenges in assessing claims efficiently. This project leverages machine learning to predict the likelihood of a claim, helping insurers reduce fraud, improve efficiency, and assist customers in faster processing.

The app allows users to:

* Upload or enter claim-related details.
* Get instant predictions on claim approval.
* Visualize model insights and performance.

---

## ⚙️ Tech Stack

* **Python 3.9+**
* **Streamlit** – for interactive UI
* **Pandas, NumPy** – for data handling
* **Scikit-learn** – for machine learning models
* **Matplotlib / Seaborn** – for data visualization

---

## 📊 Dataset

* Contains customer demographics, policy details, and claim history.
* Features include: age, gender, policy type, claim amount, accident history, etc.
* Target variable: `Claim_Status` (Approved / Not Approved).

---

## 🧠 Machine Learning Approach

1. **Data Preprocessing**

   * Handling missing values
   * Encoding categorical variables
   * Feature scaling

2. **Modeling**

   * Logistic Regression
   * Random Forest
   * XGBoost

3. **Evaluation Metrics**

   * Accuracy
   * Precision, Recall, F1-score
   * ROC-AUC

---

## 🚀 Installation & Usage

Clone the repository:

```bash
git clone https://github.com/your-username/insurance-claim-prediction.git
cd insurance-claim-prediction
```

Create a virtual environment & install dependencies:

```bash
pip install -r requirements.txt
```

Run the Streamlit app:

```bash
streamlit run app.py
```

---



## 🔮 Future Work

* Improve dataset size and feature richness.
* Deploy with Docker for scalability.
* Integrate with real-time insurance APIs.
* Experiment with deep learning models.

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repo and submit a PR.

---

## 📜 License

This project is licensed under the MIT License.


