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
├── src/
├── notebooks/
├── plots/
├── references
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
9. Compare with Traditional Methods

---

## 📊 Results

The LSTM Autoencoder successfully models normal temporal behavior and detects anomalous sequences using reconstruction error. The model's performance is compared against traditional anomaly detection algorithms, demonstrating the effectiveness of deep learning for time series anomaly detection.

---

## 📸 Output

The project generates:

- Training Loss Curve
- Reconstruction Error Plot
- Reconstruction Error Distribution
- Confusion Matrix
- Classification Report
- Comparative Results

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

**Washington State Electric Vehicle Population Dataset**

Download from the official data source and place it inside the `data/` directory.

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

## ⭐ Support

If you found this project helpful, please consider giving it a ⭐ on GitHub.
