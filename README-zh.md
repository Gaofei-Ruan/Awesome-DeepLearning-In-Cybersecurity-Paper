# 🧠 网络安全中的深度学习论文精选（Awesome Deep Learning in Cybersecurity）

[![GitHub Stars](https://img.shields.io/github/stars/ruangaofei/Awesome-DeepLearning-In-Cybersecurity-Paper?style=social)](https://github.com/ruangaofei/Awesome-DeepLearning-In-Cybersecurity-Paper/stargazers)
[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Last Update](https://img.shields.io/badge/Last_Update-2025年6月-blue)]()

🌍 本项目另有英文版本：[English Version](README.md)

---

## 📑 目录

- [📚 1. 综述与指导类](#-1-综述与指导类)
- [🌐 2. 网络流量分析](#-2-网络流量分析)
  - [2.1 入侵检测](#21-入侵检测)
  - [2.2 加密流量分类](#22-加密流量分类)
- [🚨 3. 告警与日志分析](#-3-告警与日志分析)
  - [3.1 网络告警日志](#31-网络告警日志)
- [🧩 后续计划](#-后续计划)
- [📄 许可协议](#-许可协议)

---

## 📚 1. 综述与指导类

### 🧾 Dos and Don’ts of Machine Learning in Computer Security（USENIX Security 2022）
- **方法**：经验指南  
- **链接**：[论文地址](https://www.usenix.org/conference/usenixsecurity22/presentation/arp)  
- **简介**：回顾了过去十年在顶级安全会议中应用机器学习的方法与教训，提出了网络安全中使用机器学习的最佳实践与常见误区。

---

## 🌐 2. 网络流量分析

### 2.1 入侵检测

#### 🧾 Outside the Closed World（IEEE S&P 2010）
- **方法**：经验反思  
- **链接**：[论文地址](https://ieeexplore.ieee.org/abstract/document/5504793)  
- **简介**：经典论文，深入探讨了在入侵检测中使用机器学习面临的挑战与限制，对领域研究影响深远。

#### 🧾 Kitsune: 基于自编码器的轻量级入侵检测（NDSS 2018）
- **方法**：自编码器集成  
- **链接**：[论文地址](https://arxiv.org/abs/1802.09089)  
- **简介**：提出了一种面向在线检测的轻量级入侵检测系统，使用多个自编码器学习正常行为，实现异常检测，无需监督训练。

### 2.2 加密流量分类

#### 🧾 ET-BERT：用于加密流量的预训练Transformer模型（WWW 2022）
- **方法**：预训练（BERT）  
- **链接**：[论文地址](https://dl.acm.org/doi/fullHtml/10.1145/3485447.3512217)  
- **简介**：将加密流量划分为突发（Burst）结构并转化为Tokens，基于BERT进行建模，并构建了首个面向TLS 1.3的加密流量数据集。

---

## 🚨 3. 告警与日志分析

### 3.1 网络告警日志

#### 🧾 DeepLog：基于深度学习的日志异常检测（CCS 2017）
- **方法**：序列建模（待补全）  
- **链接**：[论文地址](https://dl.acm.org/doi/abs/10.1145/3133956.3134015)  
- **简介**：*（待完善）*

#### 🧾 DEEPCASE：半监督告警事件聚类与解释（IEEE S&P 2022）
- **方法**：注意力机制 + GRU  
- **链接**：[论文地址](https://ieeexplore.ieee.org/abstract/document/9833671/)  
- **简介**：针对单条日志构建设备日志序列，通过GRU提取上下文语义，并用注意力建模日志之间的关联性，实现可解释的事件聚类。

---

## 🧩 后续计划

- [ ] 增补主机日志分析相关工作  
- [ ] 补充开源数据集与benchmark链接  
- [ ] 按深度学习架构分类（如CNN, RNN, Transformer）  
- [ ] 增加方法标签（如无监督、半监督、自监督）  

---

## 📄 许可协议

本项目基于 MIT 协议开源发布。
