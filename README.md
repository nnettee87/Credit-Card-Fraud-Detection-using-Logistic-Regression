
# 💳 Credit Card Fraud Detection using Logistic Regression

> A data science project to detect fraudulent credit card transactions using logistic regression.  
> Built with love and purpose to tackle financial fraud in Kenya and beyond. 🇰🇪💡

---

## 📌 Project Overview

Credit card fraud is a growing concern in today’s digital financial ecosystem. This project uses a logistic regression model to identify fraudulent transactions based on features such as transaction amount, time, and device/location behavior.  

Although this is a **simulated dataset**, the methodology is aligned with real-world applications and highlights how data science can protect people from financial loss.

---

## 🧠 Key Features

- Simulated dataset with over 10,000 transactions.
- Binary classification using **Logistic Regression**.
- Feature scaling with `StandardScaler`.
- Performance evaluation with **confusion matrix** and **classification report**.
- Baseline results and limitations explained.
- Future improvements suggested (SMOTE, threshold tuning, ensemble models).

---

## 🛠️ Technologies Used

- Python 3.x  
- NumPy  
- Pandas  
- scikit-learn  
- Matplotlib / Seaborn *(optional for visuals)*

---

## 📊 Results Snapshot

| Metric        | Legitimate (0) | Fraudulent (1) |
|---------------|----------------|----------------|
| Precision     | 0.981          | 0.000          |
| Recall        | 1.000          | 0.000          |
| F1-Score      | 0.990          | 0.000          |

⚠️ The model is accurate for legitimate transactions but fails to detect fraudulent ones due to **class imbalance** (only 2% fraud cases). This demonstrates a **critical real-world problem** in fraud detection: **false security** due to imbalanced data.

---

## 🚀 Future Work

To improve detection of fraudulent activity:
- [ ] Implement **SMOTE** or **ADASYN** for balancing the dataset.
- [ ] Use **class weights** in logistic regression.
- [ ] Try **Random Forest**, **XGBoost**, or **Neural Networks**.
- [ ] Analyze feature importance.
- [ ] Deploy a basic Flask API for real-time scoring.

---

## 🧩 File Structure

```
├── credit_card_fraud_logistic.ipynb   # Main notebook
├── README.md                          # Project documentation
└── requirements.txt                   # (Optional) for environment setup
```

---

## ❤️ Author

👩🏾‍💻 Ann Moraa (aka **Blue**)  
Data Science | Financial Risk | AI for Impact  
[LinkedIn](https://www.linkedin.com/in/annmoraa) | [Twitter](https://twitter.com/yourhandle) | [Website](https://yourportfolio.com)

---

## 📬 Let’s Connect

If this project inspires you, feel free to fork, star ⭐, or contribute. I’m open to collaborations, freelance projects, and data discussions—especially those that make a real difference.  

> "Data is powerful. But using it to protect people—that’s where the real power lies."
