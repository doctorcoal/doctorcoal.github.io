---
permalink: /projects/
title: "Projects"
author_profile: true
---

[中文版](/zh/projects/)

## Automated Lightweight Design for Vision Algorithms (Industry Collaboration)
**2026.03 – 2026.09 · with Shanghai Institute of Mechanical and Electrical Engineering (SAST, 航天八院) · Core member**

- **Goal**: automated lightweight design for vision algorithms running on embedded real-time inference platforms in defense-grade equipment
- **Role**: modularized our research combinational-compression framework into a reusable toolchain with clean interfaces; led integration, deployment, and on-device verification against production algorithms
- **Outcome**: an automated compression toolchain supporting ONNX / PyTorch / TensorFlow2 models and covering YOLO / ResNet, DeiT, LSTM, etc.; under a ≤ 2% accuracy-loss constraint, reducing **50–95%** compute and **50–90%** memory footprint across target algorithms

## RL-based Automated Search for Combinational Compression (Research)
**2024.09 – present · ECHSL, Shanghai Jiao Tong University**

- **Motivation**: single-method compression is nearing its marginal returns; combinational compression has huge potential, but manual policy design relies on expert experience and exhaustive search is exponentially expensive
- **Innovation**: unified modeling of method selection, ordering, and degree as a Markov decision process; built the compression environment with redesigned state / action / reward representations, plus invalid-action masking and path caching for efficient policy search
- **Results**: ~**30–100×** theoretical BitOps speedup on ResNet / MobileNet / DeiT over CIFAR-100 and ImageNet; **2–5×** real inference speedup and **3–6×** memory reduction; published at **DATE 2026 (Oral)**

## Fine-Grained Early-Exit Prediction for Computation- and Energy-Efficient Inference (Research)
**2022.09 – 2024.06 · ECHSL, Shanghai Jiao Tong University**

- **Motivation**: early exiting is central to dynamic inference, but passive schemes must execute exit layers one by one to decide, blocking system/hardware pre-optimization and incurring heavy exit overhead
- **Innovation**: proactive exit prediction that infers the optimal depth directly from early-layer features; a low-cost prediction engine (1-D iterative convolution) with unified exit layers, co-designed with processor power management and run-time scheduling for joint speed-energy-accuracy-real-time optimization
- **Results**: on server and embedded GPU platforms, up to **83%** energy saving and **2.6×** speedup for ResNet34 FP32/INT8; published at **AAAI 2023 (Oral), DAC 2023 (Oral), and IEEE TCAD 2025**

## JiaoLong RoboMaster Team · Mechatronics Engineer (Competition)
**2018.11 – 2020.11 · RoboMaster University Championship (RMUC)**

- **Role**: led the "Infantry" and "Hero" robot groups (~10 members), later served as head of the mechanical division (~30 members), managing robot R&D and testing
- **Outcome**: led projects including an adaptive suspension, a low-inertia gimbal, a high-precision small-projectile launcher, and a Mecanum-chassis climbing module, all deployed on competition robots; the team won the **Grand Prize (特等奖)** in the national finals and a **National First Prize**
