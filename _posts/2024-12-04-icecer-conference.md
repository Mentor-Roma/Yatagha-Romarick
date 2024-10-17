---
title: "Presenting at IEEE ECE 2024 in Botswana"
categories:
  - Conference
tags:
  - chat
  - Post Formats
  - security
---

I am excited to share that my paper titled "ML-based Synthetic OPC UA Traffic Generation for Covert Channel Transmission" has been accepted for presentation at the IEEE International Conference for Electrical and Computer Engineering Research (ICECER 2024) in Botswana. This paper presents an innovative approach for generating synthetic OPC UA traffic to address cybersecurity challenges in industrial automation systems, particularly concerning covert channel attacks.

The research introduces a hybrid model combining Variational Autoencoders (VAE) and Long Short-Term Memory (LSTM) networks to generate realistic, privacy-preserving synthetic data for OPC UA networks. OPC UA is a widely used protocol in industrial environments, known for its versatility and secure data exchange capabilities. However, the sensitive nature of OPC UA traffic makes it vulnerable to covert channel attacks, which can exploit legitimate communication protocols to transmit unauthorized information covertly.

By using the VAE-LSTM hybrid model, we can generate synthetic traffic that closely resembles real OPC UA traffic, including the embedding of covert messages. This allows for a detailed analysis of covert channel behavior without the risks associated with using actual operational data. In the study, we demonstrated the effectiveness of our model by successfully embedding and transmitting covert messages using two distinct methods: sequential length and payload parity. These methods were used to encode information within the packet sizes and payload characteristics, providing a valuable dataset for researchers to develop and evaluate mitigation strategies against covert channel attacks.

Presenting this work at IEEE ECE 2024 is a significant opportunity to discuss the implications of covert channels in industrial networks and to explore future research directions for enhancing cybersecurity in industrial control systems. The feedback and insights gained from this conference will help further refine our approach and contribute to the development of robust security measures in industrial environments.