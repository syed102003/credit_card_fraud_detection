# 💳 Credit Card Fraud Detection – Exploratory Data Analysis (EDA)

This project performs an in-depth **Exploratory Data Analysis (EDA)** on the popular **Credit Card Fraud Detection dataset**, which contains anonymized transaction data and a binary fraud label.  
The objective is to understand fraud patterns, class imbalance, feature behavior, and correlations to support fraud-detection model development.

---

## 📂 Dataset

The dataset is large (150+ MB), so it has been stored on Google Drive.

👉 **Download Dataset (Google Drive):**  
https://drive.google.com/drive/folders/1__Akpt0LnQCVDlgNmKVORc7GhhdZh0iq?usp=sharing

After downloading, place **creditcard.csv** into your project folder.

---


---

## 🧠 Project Overview

Credit card fraud is a major problem globally, with fraud occurring in less than **0.2%** of all transactions.  
This dataset is highly imbalanced and includes:

- **Time** – time elapsed between transactions  
- **Amount** – transaction amount  
- **V1–V28** – PCA-transformed features  
- **Class** – `1 = fraud`, `0 = non-fraud`

This project includes:

- Dataset loading & cleaning  
- Class imbalance analysis  
- Transaction patterns by time & amount  
- Distribution of all PCA features  
- Correlation matrix  
- Fraud vs Non-fraud behavior  
- Visualization of important fraud indicators  

---

## 🐍 Required Libraries

Install the required dependencies using:

```bash
pip install pandas numpy seaborn matplotlib

---

I





