
# Anomaly-Based Intrusion Detection System (AIDS) Benchmarking using Machine Learning

## 👥 Team Members

- **Abishek R** (22MIA1003)  
- **M Vishal** (22MIA1014)

---

## 📘 Introduction

An **Intrusion Detection System (IDS)** is a critical component for detecting unauthorized or malicious activities in computer networks. This project focuses on **Anomaly-Based Intrusion Detection Systems (AIDS)**, which use **machine learning (ML)** and **deep learning (DL)** techniques to detect anomalies.

Traditional studies often suffer from:
- Random model selections  
- Use of outdated or non-representative datasets  
- Lack of depth in evaluation  

To overcome these challenges, we conducted a **comprehensive benchmarking** of 10 different ML models using the **CICIDS2017** dataset, which contains diverse real-world attack scenarios and is notably **highly imbalanced**.

---

## ⚙️ Project Workflow

1. **Dataset Selection**: CICIDS2017  
2. **Preprocessing**: Cleaning, feature selection, and normalization  
3. **Model Implementation**  
4. **Evaluation Metrics Analysis**  
5. **Benchmarking of Supervised & Unsupervised Models**  
6. **Result Visualization and Analysis**

---

## 🧠 ML Models Evaluated

### 🔍 Supervised Learning Models
- Decision Tree (DT)  
- Random Forest (RF)  
- Naive Bayes (NB)  
- Artificial Neural Network (ANN)  
- K-Nearest Neighbors (KNN)  
- Convolutional Neural Network (CNN)  
- Support Vector Machine (SVM)

### 🎯 Unsupervised Learning Models
- K-Means Clustering  
- Expectation-Maximization (EM)  
- Self-Organizing Map (SOM)

---

## 📊 Evaluation Metrics

- **Accuracy**  
- **Precision**  
- **Recall**  
- **F1 Score**  
- **Training Time**  
- **Testing Time**

---

## 🔬 Experimental Results

- The **KNN**, **Decision Tree**, and **Random Forest** models delivered the **best overall performance**, especially in detecting **web-based attacks**.
- These models scored the highest on **accuracy, precision, recall, and F1-score**, and showed **efficient computation time**.
- Other models had irregular performance when tested on multiclass, real-world data, showing their limitations.

### 📈 Benchmark Graphs
> Refer to the GitHub repository for detailed **graphs and visual results** on training/testing times and F1-scores across models and attack types.

---

## 📂 Dataset Used

**CICIDS2017**  
- Developed by the Canadian Institute for Cybersecurity  
- Contains benign and real-world malicious traffic  
- Multi-class classification and highly imbalanced

---

## 🛠️ Technologies Used

- Python  
- Scikit-learn  
- TensorFlow / Keras  
- Pandas, NumPy, Matplotlib  
- Jupyter Notebooks

---

## ✅ Conclusion

Through systematic benchmarking, this study identifies that **KNN, DT, and RF** are the most robust and efficient models for anomaly-based intrusion detection using the CICIDS2017 dataset. This provides valuable insights for designing efficient and accurate intrusion detection systems in cybersecurity.

---

## 📜 License

This project is licensed under the [MIT License](LICENSE)

---

## 📬 Contact

For questions or collaborations, reach out via GitHub or email.

