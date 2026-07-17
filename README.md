# 🛡️ Network Intrusion Detection System

A Machine Learning-based Network Intrusion Detection System (NIDS) developed using the **UNSW-NB15** and **NSL-KDD** datasets. This project compares multiple feature selection techniques to improve intrusion detection performance while reducing feature dimensionality.

---

## 📌 Project Overview

Network Intrusion Detection Systems (NIDS) help identify malicious network traffic by classifying normal and attack behaviors. This project evaluates several feature selection methods and dimensionality reduction techniques to analyze their impact on intrusion detection accuracy and computational efficiency.

---

## 🎯 Objectives

- Detect malicious network traffic using Machine Learning.
- Compare different feature selection techniques.
- Reduce dimensionality while maintaining model performance.
- Evaluate feature selection methods using the UNSW-NB15 and NSL-KDD datasets.

---

## 📂 Repository Structure

```
Network-Intrusion-Detection-System
│
├── ICA
│   ├── UNSW-ICA-10.ipynb
│   ├── UNSW-ICA-20.ipynb
│   └── UNSW-ICA-30.ipynb
│
├── PCA
│   ├── UNSW-PCA-10.ipynb
│   ├── UNSW-PCA-20.ipynb
│   └── UNSW-PCA-30.ipynb
│
├── RFE
│   ├── IDS_UNSW_RFE_10_20.ipynb
│   └── IDS_UNSW_RFE_30.ipynb
│
├── SFS
│   ├── IDS_UNSW_SFS_10.ipynb
│   ├── IDS_UNSW_SFS_20.ipynb
│   └── IDS_UNSW_SFS_30.ipynb
│
├── PSO
│   └── PSO-PCA30-UNSW.ipynb
│
├── NSL-KDD
│   └── NSL-KDD_ALL_FEATURES_SELECTION_METHODS.ipynb
│
└── README.md
```

---

## 📊 Feature Selection Techniques

- Principal Component Analysis (PCA)
- Independent Component Analysis (ICA)
- Recursive Feature Elimination (RFE)
- Sequential Feature Selection (SFS)
- Particle Swarm Optimization (PSO)

---

## 📁 Datasets

### UNSW-NB15
- Modern network intrusion dataset containing normal and malicious network traffic.
- Used for evaluating feature selection techniques.

### NSL-KDD
- Improved version of the KDD Cup 1999 dataset.
- Used for benchmarking intrusion detection algorithms.

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

---

## 🚀 Project Workflow

1. Data Preprocessing
2. Feature Selection
3. Dimensionality Reduction
4. Model Training
5. Performance Evaluation
6. Comparative Analysis

---

## 📈 Feature Selection Experiments

| Technique | Components/Features |
|-----------|---------------------|
| ICA | 10, 20, 30 |
| PCA | 10, 20, 30 |
| RFE | Multiple Feature Sets |
| SFS | 10, 20, 30 |
| PSO | Optimized Feature Selection |

---

## 💡 Applications

- Cybersecurity
- Network Traffic Analysis
- Intrusion Detection Systems
- Threat Detection
- Security Analytics

---

## 👨‍💻 Author

**Vuyyuru Sriram Lokesh**

- GitHub: https://github.com/Lokeshvuyyuru

---

## ⭐ If you find this repository useful, consider giving it a Star!
