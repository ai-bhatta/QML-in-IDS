# Quantum Machine Learning (QML) for Intrusion Detection System (IDS)

Preprocessing Pipeline
This repository contains the **basic preprocessing pipeline** for the Quantum Machine Learning (QML) model aimed at **Intrusion Detection Systems (IDS)**. The preprocessing step is an essential part of the full model pipeline, ensuring that raw IoT network traffic data is cleaned, normalized, and prepared for downstream quantum-based classification tasks.

> **Note:** Only the **basic preprocessing** notebook is uploaded here.  
> Further model development and experiments (including Quantum Support Vector Machines, Quantum Random Forests, and Quantum-enhanced Clustering) are currently **under construction** and will be released in a future update.

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

The project uses the **Ton-IoT** dataset for IoT network intrusion detection research.

You can download the dataset from:  
🔗 [Ton-IoT Dataset – UNSW Canberra](https://research.unsw.edu.au/projects/toniot-datasets)

---

## 🚀 Future Work

The full repository (to be uploaded soon) will include:
- **Quantum Support Vector Machine (QSVM)** for classification
- **Quantum Random Forest (QRF)** for decision-based detection
- **Quantum-enhanced K-Means clustering** for unsupervised anomaly detection
- Comparative analysis of quantum vs classical approaches

---

## 🛠 Requirements

To run the preprocessing pipeline, install the following dependencies:

```bash
pip install pandas numpy scikit-learn
