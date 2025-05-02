# ECGClassificationDeepLearning

# 🫀 ECG Classification Using Deep Learning (Capstone Aim 2)

This repository contains the complete implementation, experiments, and report for my capstone project titled:

**"Advanced ECG Classification Using Deep Learning: A Comparative Study of 1D CNN and Dual-Branch CNN Models"**

UNC Charlotte  
ITCS 5356 – Intro to Machine Learning  
Instructor: Prof. Xiang Zhang  
Author: Akriti Saxena (UNCC ID: 801367163)  
Date: May 4, 2025

---

## 📌 Project Objective

To investigate and compare the performance of advanced deep learning methods for classifying ECG signals into five heartbeat categories using the ECG5000 dataset. I implemented and evaluated:

- **Method A**: One-Dimensional CNN (1D CNN)
- **Method B**: Dual-Branch CNN (Time-domain + Frequency-domain via FFT)
- **Method C**: K-Nearest Neighbors (KNN) as a baseline


---

## 🧠 Methods Summary

### 🔹 Method A – 1D CNN
Implemented based on *Hemaxi et al. (2024)*. Operates on raw ECG time-series data using stacked Conv1D layers. Focused on capturing waveform morphology.

### 🔹 Method B – Dual-Branch CNN
Inspired by *Shaik et al. (2023)*. Processes raw ECG signal and FFT-transformed signal in parallel branches. Outputs are fused for final classification.

### 🔹 Method C – KNN Baseline
Simple, distance-based classifier used to benchmark deep learning models.

---

## 📊 Results Summary

| Metric         | Method A | Method B | Method C |
|----------------|----------|----------|----------|
| Accuracy       | 95.00%   | 95.20%   | 92.60%   |
| Macro F1-Score | 0.51     | 0.59     | 0.57     |
| Recall (macro) | 0.49     | 0.54     | 0.53     |

---

## 📚 References

1. Hemaxi, N., et al. (2024). *Deep Learning for ECG Classification: A Comparative Study of 1D and 2D Representations...* [DOI](https://doi.org/10.1016/j.bspc.2023.105196)
2. Shaik, S., et al. (2023). *Classification of ECG Signal Using FFT-Based Improved AlexNet Classifier* [DOI]([https://doi.org/10.1016/j.jksuci.2023.101367](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0274225))
3. Pałczyński, K., et al. (2022). *Few-Shot Learning for ECG Classification* [DOI](https://doi.org/10.3390/s22030904)
4. UCI ML Repository: [ECG5000 Dataset](https://archive.ics.uci.edu/ml/datasets/ECG5000)

---

## 🙋 Author

**Akriti Saxena**  
M.S. in Information Technology  
University of North Carolina at Charlotte  

---
