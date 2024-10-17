---
title: "Zero-Day Anomaly Detection in Cyber-Physical Systems: CIKM 2024"
categories:
  - Conference
tags:
  - chat
  - Post Formats
  - security
---

At the CIKM 2024 conference in Idaho USA, I presented my paper titled "Towards a Zero-Day Anomaly Detector in Cyber-Physical Systems Using a Hybrid VAE-LSTM-OCSVM Model." The paper introduces a sophisticated anomaly detection architecture designed to safeguard critical cyber-physical systems (CPS) from unforeseen operational disruptions. The hybrid model leverages Variational Autoencoders (VAE), Long Short-Term Memory (LSTM) networks, and One-Class Support Vector Machine (OCSVM) to detect both known and unknown anomalies in CPS environments.

The primary focus of the research is to enhance system resilience by identifying deviations from normal system operations without requiring prior knowledge of specific anomalies—making it an effective "zero-day" anomaly detector. The VAE is used to learn the underlying latent representation of the system's normal behavior, while the LSTM captures temporal patterns. The OCSVM layer further analyzes the latent space to detect anomalies that might not be evident from reconstruction error alone.

The study also introduces an Adaptive Loss Weight Adjustment Algorithm (ALWAA) to adapt the model to domain changes in real-time, ensuring the model remains effective in continually evolving environments. This continual learning approach allows the anomaly detector to maintain performance even in non-stationary conditions, where traditional methods would degrade.

The experimental setup involved deploying the model on a Raspberry Pi 400, demonstrating its applicability in resource-constrained environments typical of industrial settings. The results highlighted the model's superior ability to detect both point and contextual anomalies, providing an essential tool for enhancing security and operational reliability in CPS.

Presenting at CIKM 2024 was an excellent opportunity to discuss these advancements with experts in the field, receive feedback, and explore collaborative opportunities for future research in enhancing the resilience of critical infrastructures.