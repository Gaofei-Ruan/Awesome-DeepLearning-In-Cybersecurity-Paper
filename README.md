# 🧠 Awesome Deep Learning in Cybersecurity Papers

[![GitHub Stars](https://img.shields.io/github/stars/Gaofei-Ruan/Awesome-DeepLearning-In-Cybersecurity-Paper?style=social)](https://github.com/ruangaofei/Awesome-DeepLearning-In-Cybersecurity-Paper/stargazers)
[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Last Update](https://img.shields.io/badge/Last_Update-June_2025-blue)]()

🌍 This README is also available in: [简体中文 (Chinese)](README-zh.md)

---

## 📑 Table of Contents

- [📚 1. Survey & Guidelines](#-1-survey--guidelines)
- [🌐 2. Traffic Analysis](#-2-traffic-analysis)
  - [2.1 Network Intrusion Detection](#21-network-intrusion-detection)
  - [2.2 Encrypted Traffic Classification](#22-encrypted-traffic-classification)
- [🚨 3. Alert and Log Analysis](#-3-alert-and-log-analysis)
  - [3.1 Network Alert Logs](#31-network-alert-logs)
- [🧩 To-Do](#-to-do)
- [📄 License](#-license)

---

## 📚 1. Survey & Guidelines

### 🧾 Dos and Don’ts of Machine Learning in Computer Security (USENIX Security 2022)
- **Method**: Guide  
- **Link**: [Paper](https://www.usenix.org/conference/usenixsecurity22/presentation/arp)  
- **Summary**: A comprehensive review of 10 years of ML applications in top security venues. Summarizes best practices and common pitfalls for applying ML in security research.

---

## 🌐 2. Traffic Analysis

### 2.1 Network Intrusion Detection

#### 🧾 Outside the Closed World (IEEE S&P 2010)
- **Method**: Guide  
- **Link**: [Paper](https://ieeexplore.ieee.org/abstract/document/5504793)  
- **Summary**: Discusses challenges in applying machine learning to intrusion detection. A foundational paper that highlights domain-specific limitations.

#### 🧾 Kitsune: An Ensemble of Autoencoders for Online NIDS (NDSS 2018)
- **Method**: Autoencoder Ensemble  
- **Link**: [Paper](https://arxiv.org/abs/1802.09089)  
- **Summary**: Online, lightweight network intrusion detection using a set of autoencoders to learn normal behavior and detect anomalies.

### 2.2 Encrypted Traffic Classification

#### 🧾 ET-BERT: Pretrained Transformer for Encrypted Traffic (WWW 2022)
- **Method**: Pre-training (BERT)  
- **Link**: [Paper](https://dl.acm.org/doi/fullHtml/10.1145/3485447.3512217)  
- **Summary**: Introduces ET-BERT, which tokenizes burst-structured encrypted flows using BERT. Also proposes the first dataset for TLS 1.3 encrypted traffic classification.

---

## 🚨 3. Alert and Log Analysis

### 3.1 Network Alert Logs

#### 🧾 DeepLog: Anomaly Detection from Logs (CCS 2017)
- **Method**: Guide  
- **Link**: [Paper](https://dl.acm.org/doi/abs/10.1145/3133956.3134015)  
- **Summary**: *(To be completed)*

#### 🧾 DEEPCASE: Semi-Supervised Contextual Log Clustering (IEEE S&P 2022)
- **Method**: Attention + GRU  
- **Link**: [Paper](https://ieeexplore.ieee.org/abstract/document/9833671/)  
- **Summary**: Builds GRU-based embeddings for log sequences and uses attention to model inter-log relevance. Supports semi-supervised clustering and interpretation of alerts.

---

## 🧩 To-Do

- [ ] More papers on host log analysis
- [ ] Add benchmark links
- [ ] Classify by DL architecture
- [ ] Add paper tags (e.g., supervised, unsupervised, contrastive)

---

## 📄 License

This project is licensed under the MIT License.
