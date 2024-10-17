---
title: "Assessing Anomaly Detection in Resource-Constrained Environments: ICCP 2024"
categories:
  - Conference
tags:
  - chat
  - Post Formats
  - security
---
At the IEEE ICCP 2024 conference in Romania, I presented my paper titled "Assessing the Complexity and Real-Time Performance of Anomaly Detection Algorithms in Resource-Constrained Environments." This research addresses the challenges of deploying machine learning-based anomaly detection algorithms in environments with limited computational resources, such as Industrial Internet of Things (IIoT) setups and edge devices.

The paper systematically evaluated several commonly used models, including Random Forests, Support Vector Machines (SVM), XGBoost, Neural Networks, and Autoencoders. We compared their computational complexity and practical feasibility using both theoretical analysis and empirical testing across four different datasets. Our findings highlighted the trade-offs between model complexity, accuracy, and real-time performance, especially when deploying on devices like Raspberry Pi that have constrained resources.

One of the key outcomes of this research was the development of a decision matrix to assist stakeholders in selecting appropriate models based on specific operational constraints. The study found that while Neural Networks and Autoencoders provide high accuracy, they require significant optimization to meet real-time processing demands on edge devices. On the other hand, simpler models like Random Forests and XGBoost offered a better balance between resource efficiency and performance, making them suitable for specific real-world applications.

Presenting this work at ICCP 2024 allowed me to discuss these findings with experts in the field, explore new ideas for optimizing anomaly detection, and highlight the importance of achieving a balance between performance and resource constraints in critical applications.