# 🧠 网络安全中的深度学习论文精选（Awesome Deep Learning in Cybersecurity）

[![GitHub Stars](https://img.shields.io/github/stars/ruangaofei/Awesome-DeepLearning-In-Cybersecurity-Paper?style=social)](https://github.com/ruangaofei/Awesome-DeepLearning-In-Cybersecurity-Paper/stargazers)
[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

🌍 本项目的 [English Version](README.md)

## 📑 目录

- [1. 综述与指南类论文](#-1-综述与指南类论文)
- [2. 网络流量分析](#-2-网络流量分析)
  - [2.1 网络入侵检测](#21-网络入侵检测)
  - [2.2 加密流量分析](#22-加密流量分析)
- [3. 告警与日志分析](#-3-告警与日志分析)
  - [3.1 网络日志告警](#31-网络日志告警)
- [待补充事项](#-待补充事项)
- [许可证](#-许可证)

[![Last Update](https://img.shields.io/badge/最后更新-June_2025-blue)]()

🌍 本项目的 [English Version](README.md)

本项目整理了应用 **深度学习（Deep Learning）** 方法于各类 **网络安全任务** 的研究论文，按主题分类，持续更新。

---

## 📚 1. 综述与指南类论文

| 方法 | 标题 | 简介 |
|------|------|------|
| 指南类 | [**(USENIX Security 2022)** Dos and Don’ts of Machine Learning in Computer Security](https://www.usenix.org/conference/usenixsecurity22/presentation/arp) | 回顾 ML 在顶会安全论文中的应用，总结安全领域中 ML 使用的注意事项。 |

---

## 🌐 2. 网络流量分析

### 2.1 网络入侵检测

| 方法 | 标题 | 简介 |
|------|------|------|
| 指南类 | [**(IEEE S&P 2010)** Outside the Closed World](https://ieeexplore.ieee.org/abstract/document/5504793) | 介绍 ML/DL 在流量异常检测中的局限性。 |
| 自编码器集成 | [**(NDSS 2018)** Kitsune](https://arxiv.org/abs/1802.09089) | 轻量级无监督 NIDS，基于多个自编码器学习正常流特征。 |

### 2.2 加密流量分析

| 方法 | 标题 | 简介 |
|------|------|------|
| 预训练（BERT） | [**(WWW 2022)** ET-BERT](https://dl.acm.org/doi/fullHtml/10.1145/3485447.3512217) | 使用 BERT 进行加密流量分类，首次引入 TLS 1.3 数据集。 |

---

## 🚨 3. 告警与日志分析

### 3.1 网络日志告警

| 方法 | 标题 | 简介 |
|------|------|------|
| 指南类 | [**(CCS 2017)** DeepLog](https://dl.acm.org/doi/abs/10.1145/3133956.3134015) | （待补充） |
| Attention + GRU | [**(IEEE S&P 2022)** DEEPCASE](https://ieeexplore.ieee.org/abstract/document/9833671/) | 半监督聚类与解释告警日志上下文相关性。 |

---

## 🧩 待补充事项

- [ ] 增加主机日志分析类论文；
- [ ] 增加数据集与 benchmark；
- [ ] 按网络结构归类（CNN/GNN/Transformer）；
- [ ] 增加论文属性标签（如无监督等）。

---

## 📄 许可证

本项目基于 MIT License 开源。