---
permalink: /projects/
title: "Projects"
---

## OWASP Top 10 Attack Implementation & Detection in OT Environments
**Role:** Lead Researcher / Security Engineer  


### 1. Project Overview
Designed and executed a real-world OT security research project to simulate critical OWASP Top 10 attacks on an industrial testbed, followed by deploying detection mechanisms. Collaborated with interns to analyze attack patterns and develop mitigations.  


### 2. **Tools & Technologies:**  
- *Testbed:*  
    - Real PLC
    - HMI
    - Industrial Gateway
    - FortiSwitch
    - Simulated Water Control System (e.g., CORE)  
The testbed architecture is shown in ![Testbed](assets\images\testbed.png "Experimentation Testbed")  
- *Attacks Implemented:*
    - Insider Threat (Access Control Manipulation)
    - Data Exfiltration (Covert Channel)
    - Denial of Service.  
- *Detection Tools:* 
    - Snort IDS
    - Machine Learning
    - CACAO playbooks 


### 3. Attack Simulations
- *Insider Threat (Access Control Manipulation):*
    - Insider manipulates the Access Control List to grant access to outsider, and whitelists his email address for 2FA. 
    - Outsider attacker can now access the PLC remotely and modify the control logic
- *Data Exfiltration via Covert Channel:*
    - Using timing modulation, as series of bits conveying a message is transmitted from the raspberry to the outsider computer
- *Denial of Service (DoS) on OT Protocols:*
    - With VPN access to the LAN, outsider floods the controller with SYN-packets

### 4. Detection Mechanisms
- *Playbooks:*
    - Access Control List are monitored by network sensors, and a playbook is launched when any ACL modification is detected. The playbook informs the rightfull admins to verify and confirm the changes, but can also carry out automated tasks
- Signature-Based (Snort IDS):
    - Developed custom Snort rules to detect malicious pattern in the traffic data
- Anomaly Detection (Machine Learning):
    - Trained ML models (VAE-LSTM networks) on network data to flag covert channels and 
Part of research presented and published at conferences (See Publication and Post sections). Mentored interns in attack modeling, Snort rule development, and ML for OT security.




## Safety Assurance in Water Treatment Systems via Physiscs-Based & AI Anomaly Detection 

### 1. Project Overview  
Developed a dual-layer safety system for a water treatment plant to prevent unsafe state using:
- Physics-informed command validation (Deterministic)
- Behavioural anomaly detection (AI/ML-driven)

### 1. Physics-Based Command Interception & Validation
- Intercepted operator commands via OPC UA write request sensors
- Calculated system state using thermodynamic principles before execution
- Blocked commands violating safety thresholds  

### 2. AI-Driven Anomaly Detection (VAE-LSTM Hybrid)
- Variational Autoencoder: Compressed sensor data into latent space
- Long Short Term Memory: Detected temporal anomalies, using a windows of multiple system snapshots  

Both approaches are combined to block malicious or errorneous commands and detect stealthy attacks by monitoring the process data directly.




## Zero-Day Vulnerability Discovery in Safety I&C Systems via Fuzz Testing
**Role:** Fuzz Testing Engineer / Security Researcher  
**Domain:** Nuclear Industrial Safety Instrumentation & Control Systems  
**Standards:** IEC 61508 (Funtional Safety), IEC 62443 (Industrial Security)  

### 1. Project Overview
Contributed in the design and execution of a fuzz testing framework to uncover zero-day vulnerabilities in safety I&C systems used in critical infrastructures. The test is focused on disrupting malicious inputs to crash conditions, memory corruption, and logic flaws that could compromise the controller's operation

### 2. Key Contributions
- Designed python scripts used as protocol fuzzers
- Hardware-in-the-Loop testing on embedded controllers
- Analyzed crashes with GDB/Ghidra to identify and classify bugs



### Cybersecurity Research Specialist
**Role**: Cybersecurity researcher  
**Duration**: January 2022 - Present  
**Description**: 
As a cybersecurity researcher, I have worked on several projects and published scientific peer reviewed papers. For more technical details on my contribution, read my [blog post on anomaly detection and publications](/_pages/publications.md).

### SMARTEST Project
**Role**: Researcher  
**Duration**: January 2023 - April 2024  
**Description**: 
The SMARTEST project aims to develop secure, smart systems for critical infrastructure. I focused on designing and implementing machine learning algorithms for real-time anomaly detection in industrial control systems (ICS). My work involved collaborating with multidisciplinary teams, and using technologies like OPC UA and predictive maintenance to ensure resilient operations. 

**Technologies**: Python, OPC UA, Jupyter, Machine Learning


### SYNAPSE EU Horizon Project
**Role**: Researcher  
**Duration**: August 2023 - Present  
**Description**: 
The SYNAPSE project focuses on the development of innovative cybersecurity solutions for critical infrastructure. I joined the project during its first plenary meeting in Rome, where we aligned goals and collaborated on designing a secure architecture for cyber-physical systems.


### Computer Science Laboratory Coordinator
**Role**: Lab Coordinator 
**Duration**: September 2019 - June 2022 
**Description**: 
At this position, I was responsible for overseeing the daily operations of the ICT lab, ensuring a productive and safe working environment for students. This included maintaining and upgrading lab hardware and software, managing lab schedules, and providing technical support. I also designed lesson plans and taught courses that align with educational standards and address various aspects of ICT, such as programming, networking, and cybersecurity.

