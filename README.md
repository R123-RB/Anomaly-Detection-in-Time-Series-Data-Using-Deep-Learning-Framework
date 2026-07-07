# 📈 Anomaly-Detection-in-Time-Series-Data-Using-Deep-Learning-Framework
Academic capstone project implementing a deep learning framework for detecting anomalies in time series data using an **LSTM Autoencoder**. This project implements a hybrid anomaly detection pipeline inspired by **Sathe & Shinde (2024)**.

---

## 🚀 Project Overview

Anomaly detection in time series data is essential in domains such as predictive maintenance, fraud detection, cybersecurity, healthcare, and IoT systems. This project uses an **LSTM Autoencoder** to learn normal sequential patterns and identify anomalous observations through reconstruction error.

The implementation includes data preprocessing, normalization, sliding window sequence generation, model training, anomaly detection, visualization, and performance evaluation.

---

## ✨ Features

- Deep Learning-based LSTM Autoencoder
- Time Series Data Preprocessing
- Min-Max Normalization
- Sliding Window Sequence Generation
- Reconstruction Error-Based Anomaly Detection
- Automatic Threshold Selection
- Performance Evaluation
- Visualization of Results

---

## 🛠 Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Scikit-learn
- Matplotlib

---

## 📂 Project Structure

```
Anomaly-Detection-in-Time-Series-Data-Using-Deep-Learning-Framework/
│
├── data/
├── plots/
├── references/
├── Project_Report
├── Implimentation_code
├── requirements.txt
└── README.md
```

---

## ⚙ Workflow

1. Load Dataset
2. Data Cleaning & Preprocessing
3. Feature Normalization
4. Generate Sliding Window Sequences
5. Train LSTM Autoencoder
6. Calculate Reconstruction Error
7. Detect Anomalies
8. Evaluate Performance

---

## 📊 Results

The LSTM Autoencoder successfully models normal temporal behavior and detects anomalous sequences using reconstruction error. 

---

## 📸 Output

The project generates:

- Training Loss Curve
- Reconstruction Error Plot
- Reconstruction Error Distribution
- Confusion Matrix

---

## 💻 Installation

```bash
git clone https://github.com/R123-RB/Anomaly-Detection-in-Time-Series-Data-Using-Deep-Learning-Framework.git

cd Anomaly-Detection-in-Time-Series-Data-Using-Deep-Learning-Framework

pip install -r requirements.txt
```

---

## ▶️ Usage

```bash
python train.py
```

or execute the Jupyter Notebook.

---

## 📚 Dataset

This project uses the **Washington State Electric Vehicle Population Data** dataset, which contains information on Battery Electric Vehicles (BEVs) and Plug-in Hybrid Electric Vehicles (PHEVs) registered through the Washington State Department of Licensing.

**Dataset Source:**  
https://catalog.data.gov/dataset/electric-vehicle-population-data

The dataset is publicly available through **Data.gov** and is maintained by the **State of Washington**. :contentReference[oaicite:0]{index=0}

---

## 📖 Reference

This project is inspired by the following research paper:

> Sathe, S., & Shinde, S. (2024). **A Deep Learning Framework for Effective Anomaly Detection in Time Series Data.** *Asian Conference on Innovation in Technology (ASIANCON).* IEEE.

If you use this repository in your research, please consider citing the original paper.

---

## 🤝 Collaborators

- **Rehan Biju**
- **Akshay B S**

---

## 📄 License

This project is developed for educational and research purposes.

---
