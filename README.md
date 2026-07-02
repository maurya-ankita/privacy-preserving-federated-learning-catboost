# 🏥 Healthcare Outcome Prediction using Privacy-Preserving Federated Learning and CatBoost

## 📌 Overview

This project presents a privacy-preserving federated learning framework for healthcare outcome prediction using the CatBoost machine learning algorithm.

The implementation simulates a federated learning environment where multiple hospitals collaboratively train machine learning models without sharing patient data. To enhance privacy and security, the framework incorporates:

- Federated Learning
- FedAvg-inspired Weighted Aggregation (Fed-Avg)
- Differential Privacy
- Homomorphic Encryption (TenSEAL)

The objective is to predict patient outcomes while preserving data privacy during the learning process.

<img width="1024" height="1536" alt="ChatGPT Image Jul 2, 2026, 07_34_17 PM" src="https://github.com/user-attachments/assets/10f4d053-6c17-4652-8454-c661c9c69a06" />


---

## 🚀 Features

- Healthcare Outcome Prediction
- CatBoost Multi-Class Classification
- Federated Learning Simulation (5 Clients)
- FedAvg-inspired Weighted Aggregation
- Differential Privacy
- Homomorphic Encryption using TenSEAL
- SMOTE for Class Balancing
- Performance Evaluation and Comparison

---

## 🛠️ Technologies Used

- Python
- CatBoost
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Imbalanced-learn (SMOTE)
- TenSEAL

---

## 📊 Workflow

```
Dataset
   │
   ▼
Data Preprocessing
   │
   ▼
SMOTE Oversampling
   │
   ▼
Centralized CatBoost
   │
   ▼
Federated Learning Simulation
   │
   ▼
FedAvg-inspired Aggregation
   │
   ▼
Differential Privacy
   │
   ▼
Homomorphic Encryption
   │
   ▼
Performance Evaluation
```

---

## 📈 Experimental Results

| Method | Accuracy |
|-------------------------------|-----------|
| Centralized CatBoost | **87.40%** |
| Federated CatBoost | **86.40%** |
| CatBoost + FedAvg | **86.40%** |
| CatBoost + Differential Privacy | **85.65%** |
| CatBoost + Homomorphic Encryption | **86.40%** |
| CatBoost + DP + FedAvg | **85.65%** |
| CatBoost + HE + FedAvg | **86.35%** |

---

## ▶️ How to Run

1. Clone this repository.

```bash
git clone https://github.com/<your-username>/<repository-name>.git
```

2. Install the required dependencies.

```bash
pip install -r requirements.txt
```

3. Open the notebook.

```
Federated_Code.ipynb
```

4. Upload the dataset (`medical_data1.csv`) to the Google Colab runtime and execute all cells sequentially.

---

## 📂 Repository Structure

```
├── Federated_Code.ipynb
├── README.md
└── requirements.txt
```

---

## 📌 Future Work

- Real-world Federated Learning using Flower Framework
- Non-IID Client Distribution
- Secure Aggregation Protocols
- Adaptive Differential Privacy
- Deployment in Distributed Healthcare Environments

---

## 👩‍💻 Author

**Ankita Maurya**

M.Tech, Computer Science & Engineering, NIT Bhopal
2+ Research Publications
1 SCIE Q1 Journal in the area of Healthcare in AI

Research Interests:
- Federated Learning
- Privacy-Preserving Machine Learning
- Healthcare AI
- Machine Learning
- Data Science

---

⭐ If you find this project useful, consider giving it a star.
