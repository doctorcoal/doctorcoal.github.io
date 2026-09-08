---
permalink: /zh/publications/
title: "论文发表"
author_profile: true
---

[English version](/publications/)

## 第一作者 / 共同第一作者

**[ACL 2026] River-LLM: Large Language Model Seamless Exit Based on KV Share**
（CCF-A 会议，第一作者）
**Yingtao Shen**, An Zou.
提出免训练的解码式大语言模型词元级无缝提前退出框架，以 KV 共享退出支流消除昂贵的缓存恢复开销，使 Ministral3、Phi4、Llama3 等模型在数学推理与代码生成任务上实现 **1.71×–2.16×** 实际时钟加速。

**[DATE 2026] Compression Space Search: RL-based Combinational Compression for Neural Networks**
（CCF-B 会议，**Oral**，第一作者）
**Yingtao Shen**, Yinchen Ni, Jiace Zhu, Jie Zhao, An Zou.
将量化、剪枝、知识蒸馏、早期退出等多种模型压缩与优化方法的选型、顺序与程度建模为马尔可夫决策过程，以强化学习自动搜索最优组合压缩策略，突破单一压缩方法的性能天花板。在 CNN 与 ViT 上实现最高 **100.8×** 理论加速；在 Jetson AGX Orin 上，相比 TensorRT 充分优化的原模型仍有 **2.0–5.2×** 推理加速与 **3.3–5.4×** 显存节省。

**[IEEE TCAD 2025] LEAP: Light Weighting Neural Network Inference through Proactive Early Exiting Prediction**
（CCF-A 期刊，第一作者）
**Yingtao Shen**, Xiangjie Li, Yehan Ma, Jie Zhao, An Zou.
提出主动式早期退出预测机制，以低开销预测引擎在推理早期预判最优计算深度。对 CNN 与 ViT，在 Jetson AGX Orin 与 i7-10700 上能耗降低 **83%**、时延降低 **71%**，精度损失 1% 以内。

**[DAC 2023] EENet: Energy Efficient Neural Networks with Run-time Power Management**
（CCF-A 会议，**Oral**，共同第一作者）
Xiangjie Li\*, **Yingtao Shen\***, An Zou, Yehan Ma.
将动态提前退出与处理器运行时功耗管理（DVFS）协同设计，实现神经网络推理能耗-性能联合优化。在降低 ResNet **64%** 能耗的同时，实时性超越领域 SOTA 方法。

**[CSTIC 2023] Learning-Based Performance and Power Model for Processor Microsecond DVFS**
（会议，**Oral**，第一作者）
**Yingtao Shen**, An Zou.

## 合作作者

**[IEEE TCAD 2026] Cheerful: Hardware-Oriented Early Exits for Ubiquitous Computing**
（CCF-A 期刊）
Haolan Zhang, Jintao Chen, **Yingtao Shen**, An Zou, Yehan Ma.

**[DATE 2025] SSM DVFS: Microsecond-Scale DVFS on GPGPUs with Supervised and Self-Calibrated ML**
（CCF-B 会议）
Minqing Sun, Ruiqi Sun, **Yingtao Shen**, Wei Yan, Qinfen Hao, An Zou.

**[AAAI 2023] Predictive Exit: Prediction of Fine-Grained Early Exits for Computation- and Energy-Efficient Inference**
（CCF-A 会议，**Oral**）
Xiangjie Li, Chenfei Lou, Zhengping Zhu, Yuchi Chen, **Yingtao Shen**, Yehan Ma, An Zou.
