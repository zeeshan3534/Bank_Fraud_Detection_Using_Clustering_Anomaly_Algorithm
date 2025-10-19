# 🏦 Bank Fraud Detection Using Unsupervised Learning (Isolation Forest, LOF, DBSCAN, KMeans)

This project focuses on **detecting fraudulent banking transactions** using **unsupervised machine learning** techniques.  
Since real-world fraud datasets are often **highly imbalanced** and lack reliable labels, this notebook applies **anomaly detection algorithms** to uncover suspicious transaction patterns **without requiring pre-labeled fraud cases**.

---

## 🚀 Project Highlights

✅ **Real-world fraud challenge:** Works on unlabeled or partially labeled transaction data  
🔍 **Exploratory Data Analysis (EDA):** Understands transaction patterns and detects irregular behavior  
🛠️ **Feature Engineering:** Includes time-based features, transaction frequency, and amount deviation metrics  
📏 **Scaling & Normalization:** Prepares features for distance-based anomaly algorithms  
📉 **Dimensionality Reduction:** Uses PCA and t-SNE for high-quality fraud visualization  

🤖 **Multiple Unsupervised Models Applied:**
- **Isolation Forest** — isolates anomalies via random partitioning  
- **Local Outlier Factor (LOF)** — detects low-density regions  
- **DBSCAN** — density-based clustering to flag noise as anomalies  
- **KMeans** — uses distance-based anomaly scoring  

📊 **Visual Comparison:** Plots detected anomalies on 2D embeddings for model interpretability  

---

## 🧠 Why Unsupervised Learning for Fraud Detection?

Fraudsters constantly **change their strategies**, making traditional supervised models ineffective over time.  
Unsupervised anomaly detection helps uncover **previously unseen fraud patterns** by identifying transactions that deviate from normal customer behavior — even when no prior fraud labels exist.

---

## 📌 Tech Stack

| Category | Tools / Libraries |
|-----------|------------------|
| **Data Handling** | Pandas, NumPy |
| **Visualization** | Matplotlib, Seaborn |
| **Preprocessing** | StandardScaler, One-Hot Encoding |
| **Dimensionality Reduction** | PCA, t-SNE |
| **Anomaly Detection** | IsolationForest, LocalOutlierFactor, DBSCAN, KMeans |
| **Optimization** | GridSearchCV |



