# Enhancing Autonomous Online Intrusion Detection for IoT

This repository contains the implementation of two Python pipelines developed for the research paper:

**“Enhancing Autonomous Online Intrusion Detection for IoT with Balanced Learning, Reliable Pseudo-Labels, and Lightweight Architectures.”**

---

## 📌 Overview

This work builds upon the AOC-IDS framework (IEEE INFOCOM 2024) and proposes improvements addressing:

* Class imbalance
* Pseudo-label noise
* Poor generalization
* High computational overhead for IoT

---

## ⚙️ Pipelines Included

### 1. XGBoost-BalSamp Pipeline

* Feature engineering (e.g., total_load, rate_ratio, pkt_diff)
* Balanced sampling strategy
* Achieves **95.45% accuracy** on UNSW-NB15

### 2. Deep Learning Pipeline

**PseudoFilter + MixupAug + LiteAE**

* Confidence-based pseudo-label filtering
* Mixup data augmentation
* Lightweight Autoencoder (55% fewer parameters)

Performance:

* **Accuracy:** 90.76%
* **F1 Score:** 91.40%

---

## 📊 Dataset

* UNSW-NB15 dataset
* 175,341 training samples
* 82,332 testing samples

---

## 🧪 Key Contributions

* Reproduced AOC-IDS baseline (89.39% accuracy)
* Improved performance using XGBoost (+6.26%)
* Reduced model size by **55%** for IoT deployment
* Designed robust pseudo-label filtering

---

## 🚀 How to Run

1. Open the notebooks in Google Colab or Jupyter
2. Upload UNSW-NB15 dataset
3. Run cells sequentially

---

## 📄 Paper

This repository supports reproducible research for the paper.


---

## 📌 Notes

* Code is provided for academic and research purposes
* Dataset must be downloaded separately
