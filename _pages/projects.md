---
permalink: /projects/
title: "Projects"
---

### OWASP Top 10 Attack Simulation & Detection in OT Environments
**Role:** Lead Researcher / Security Engineer
**Tools & Technologies:**
- *Testbed:* Real PLC (e.g., Siemens S7-1500), HMI (Ignition/FactoryTalk), Industrial Gateway, FortiSwitch, Simulated Water Control System (e.g., CORE). The testbed architecture is shown in ![Testbed](images/tesbed.png "Experimentation Testbed")
- *Attacks Implemented:* Insider Threat (Access Control Manipulation), Data Exfiltration (Covert Channel), DoS.
*Detection Tools:* Snort IDS, Machine Learning, Wireshark, FortiAnalyzer.

- *Frameworks:* NIST SP 800-82 (OT Security), MITRE ATT&CK for ICS.

## Project Overview
Designed and executed a real-world OT security research project to simulate critical OWASP Top 10 attacks on an industrial testbed, followed by deploying detection mechanisms. Collaborated with interns to analyze attack patterns and develop mitigations.

Key Contributions
1. Attack Simulations
Insider Threat (Access Control Manipulation):

Insider manipulates the Access Control List to grant access to outsider, and whitelists his email address for 2FA. Outsider attacker can now access the PLC remotely and modify the control logic

Data Exfiltration via Covert Channel:

Using timing modulation, as series of bits conveying a message is transmitted from the raspberry to the outsider computer

Denial of Service (DoS) on OT Protocols:

With VPN access to the LAN, outsider floods the controller with SYN-packets

2. Detection Mechanisms
Playbooks:
Access Control List are monitored by network sensors, and a playbook is launched when any ACL modification is detected. The playbook informs the rightfull admins to verify and confirm the changes, but can also carry out automated tasks

Signature-Based (Snort IDS):

Developed custom Snort rules to detect malicious Modbus traffic (e.g., abnormal function codes, excessive requests).

Deployed on the FortiSwitch to monitor east-west traffic.

Anomaly Detection (Machine Learning):

Trained ML models (VAE-LSTM networks) on network telemetry (PCAPs) to flag covert channels and 


Part of research presented and published at conferences (See Publication and Post sections)

Mentored interns in attack modeling, Snort rule development, and ML for OT security.





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

