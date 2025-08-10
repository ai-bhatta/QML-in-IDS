# Quantum Machine Learning (QML) for Intrusion Detection (ToN-IoT Dataset)

This repository contains the **basic preprocessing pipeline** for implementing a Quantum Machine Learning based intrusion detection system using the **ToN-IoT dataset**.  
The preprocessing stage prepares the dataset for quantum machine learning experiments by handling missing values, encoding categorical variables, balancing classes, scaling features, and splitting the data into training and testing sets.  

> **Note:** Only the **basic preprocessing file** is uploaded here. Further model development, including the full QSVM training and advanced quantum-classical hybrid implementations, is **currently under construction** and will be released in future updates.

---

## 📂 Repository Contents

- `preprocessing.ipynb` – Basic preprocessing script that:
  - Loads the Ton-IoT dataset
  - Handles missing values
  - Encodes categorical variables
  - Normalizes numerical features
  - Saves the cleaned dataset for use in training quantum-based models
    
---

## 📊 Dataset

The **ToN-IoT dataset** is used in this project. It can be downloaded from the official source:  
🔗 [ToN-IoT Dataset Download](https://research.unsw.edu.au/projects/toniot-datasets)

The dataset contains network traffic data from IoT environments, making it suitable for evaluating intrusion detection models.

---

## ⚙️ Preprocessing Steps Implemented

- **Data Loading** — Reads CSV files from ToN-IoT dataset.  
- **Handling Missing Values** — Cleans the dataset.  
- **Label Encoding** — Converts categorical labels into numerical format.  
- **Standardization** — Scales features to zero mean and unit variance.  
- **Class Balancing** — Uses SMOTE for oversampling minority classes.  
- **Dimensionality Reduction** — Applies PCA *(optional)*.  
- **Train-Test Split** — Prepares data for machine learning and quantum machine learning models.  

---

## 📈 Future Work

- To implement complete **Quantum Support Vector Machine (QSVM)** classification pipeline.  
- To explore **Quantum Neural Networks (QNNs)** for intrusion detection.  
- To perform **comparative analysis** between classical and quantum models.  

---

## 🛠 Installation

To install the dependencies required for running the preprocessing and QSVM scripts, you can use the following command:

```bash
pip install -r requirements.txt
