# Debutanizer Soft Sensor using LSTM and Bi-LSTM

This project focuses on developing data-driven soft sensors for a **debutanizer column** using **Long Short-Term Memory (LSTM)** and **Bidirectional LSTM (Bi-LSTM)** neural networks. The objective is to estimate hard-to-measure process variables using historical and real-time plant data, improving process monitoring and control in an industrial setting.

---

## 📁 Files

- `Debutanizer.ipynb` — Main Jupyter notebook containing data preprocessing, model training, evaluation, and visualization.
- `data/` — Directory for raw and preprocessed debutanizer dataset (user must provide).
- `README.md` — Project description .

---

## 🔍 Project Overview

Soft sensors (or virtual sensors) are machine learning models that estimate unmeasurable or infrequently measured variables using readily available process data. This project applies LSTM-based deep learning models to build soft sensors for a debutanizer column in a refinery, which separates C4/C5 hydrocarbons.

---

## ✅ Features

- LSTM and Bi-LSTM architectures built using Keras (TensorFlow backend)
- Sequence-based time-series data preprocessing
- Model evaluation using RMSE, MAE, and visualization plots
- Bi-LSTM implementation for capturing both past and future dependencies
- Industrial relevance: targets a critical unit in petrochemical refining

---
