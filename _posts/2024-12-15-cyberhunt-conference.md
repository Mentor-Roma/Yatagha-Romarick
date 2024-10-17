---
title: "Cyber Hunt Conference in Washington DC"
categories:
  - Conference
tags:
  - Security
  - Anomaly Detection
---

I'm thrilled to announce that my paper, titled "A Combined Gradient-Based and Label-Flipping Attack on ML-Based Anomaly Detection in Cyber-Physical Systems," has been accepted for presentation at the Cyber Hunt 2024 conference in Washington, DC. This research highlights critical vulnerabilities in machine learning models used for anomaly detection in cyber-physical systems (CPS), such as water management infrastructure.

In this paper, I introduce a novel adversarial attack methodology that combines two previously distinct techniques—label-flipping poisoning and gradient-based evasion—into a unified attack strategy. This combined attack aims to bypass ML-based anomaly detection in CPS environments, making it both stealthier and more dangerous than when either technique is used independently. The gradient-based component carefully optimizes noise in input data to mislead the model, while the label-flipping component alters the labels during the poisoning process to maintain the model's apparent performance, thereby making the attack more covert.

Additionally, the paper explores model inversion attacks as a separate threat, focusing on the confidentiality and integrity of machine learning models in CPS. This attack type aims to infer sensitive information from the model, further showcasing the broad spectrum of risks faced by ML-based anomaly detection systems.

Our experimentation, involving Neural Networks, LSTM-Autoencoders, and Random Forests, demonstrates the significant vulnerabilities that arise from these adversarial techniques. By leveraging gradient optimization and label flipping, we effectively compromised anomaly detection without degrading the overall performance metrics—creating a deceptive model that appeared functional while masking critical threats.

The opportunity to present this work at Cyber Hunt 2024 is exciting, as it offers a platform to discuss the real-world implications of adversarial attacks and explore collaborative solutions for enhancing the resilience of critical infrastructures to such threats.

