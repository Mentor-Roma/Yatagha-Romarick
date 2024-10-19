---
title: "My Master's Thesis: Accelerating Fingerprint Authentication"
#last_modified_at: 2016-03-09T16:20:02-05:00
categories:
  - academic
tags:
  - Master's thesis
  - Biometric authentication
---
For my MSc in Computer Networks and Distributed Systems, I worked on a project titled "Accelerating Fingerprint Authentication with Convolutional Neural Networks." This thesis aimed to improve the efficiency of biometric authentication systems by leveraging machine learning to reduce the number of fingerprint comparisons necessary during the authentication process.

In traditional fingerprint authentication systems, incoming fingerprints are compared against every fingerprint in the database—a process that becomes increasingly time-consuming as the number of users grows. My thesis proposed a solution to this scalability issue by using Convolutional Neural Networks (CNNs) to classify fingerprints into three distinct classes. This classification step occurs before the actual comparison, effectively narrowing down the number of fingerprints that need to be evaluated to just those within a specific class.

The CNN-based classification significantly optimized the authentication process, reducing computational load and accelerating the overall matching time without compromising accuracy. By implementing this approach, fingerprint verification systems can perform faster, especially in large-scale deployments such as access control systems or national identity databases.

The project provided an excellent opportunity to combine my knowledge of computer networks, distributed systems, and machine learning. It demonstrated how CNNs could be effectively utilized not only for feature extraction but also for enhancing the scalability and efficiency of biometric authentication systems.