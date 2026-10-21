---
permalink: /projects/
title: "Projects"
author_profile: true
---

## RL-based Automated Search for Combinational Compression (Academic)
**2024.09 – present · ECHSL, Shanghai Jiao Tong University · Core R&D**

RL algorithm, environment, and search strategy design for combinational compression｜integrating quantization, pruning, dynamic inference, and distillation｜100× theoretical speedup, 5× Orin inference speedup

- **Motivation**: single-method compression is nearing its marginal returns; combinational compression has huge potential, but manual policy design relies on expert experience and exhaustive search is exponentially expensive
- **Innovation**: unified modeling of method selection, ordering, and degree as a Markov decision process; built the compression environment with redesigned state / action / reward representations, plus invalid-action masking and path caching for efficient policy search
- **Results**: ~**30–100×** theoretical BitOps speedup on ResNet / MobileNet / DeiT over CIFAR-100 and ImageNet; **2–5×** real inference speedup and **3–6×** memory reduction on Jetson AGX Orin; published at **DATE 2026 (Oral)**

## Fine-Grained Early-Exit Prediction for Computation- and Energy-Efficient Inference (Academic)
**2022.09 – 2024.06 · ECHSL, Shanghai Jiao Tong University · Core R&D**

Proactive DNN early-exit prediction co-designed with DVFS｜up to 83% energy saving and 2.6× speedup on embedded CPUs and SoC GPUs

- **Motivation**: early exiting is central to dynamic inference, but passive schemes must execute exit layers one by one to decide, blocking system/hardware pre-optimization and incurring heavy exit overhead
- **Innovation**: proactive exit prediction that infers the optimal depth directly from early-layer features; a low-cost prediction engine (1-D iterative convolution) with unified exit layers, co-designed with processor power management and run-time scheduling for joint speed-energy-accuracy-real-time optimization
- **Results**: on i7-10700 and Jetson TX2, up to **83%** energy saving and **2.6×** speedup for ResNet34 FP32/INT8 and other models; published at **AAAI 2023 (Oral), DAC 2023 (Oral), and IEEE TCAD 2025**

## RoboMaster Competition Robot R&D (Competition)
**2018.11 – 2020.11 · Yunhan JiaoLong Robotics Team, SJTU · Head of Mechanical Division / Mechatronics Engineer**

- **Role**: led the "Infantry" and "Hero" robot groups (~10 members), later served as head of the mechanical division (~30 members), managing robot R&D and testing
- **Outcome**: led projects including a Mecanum-chassis adaptive suspension, a low-inertia high-precision small-projectile gimbal launching system, and a Mecanum-chassis climbing module, all deployed on competition robots; won the **Grand Prize (特等奖)** in the RoboMaster University Championship national finals as a core team member
