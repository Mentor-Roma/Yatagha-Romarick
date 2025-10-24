---
permalink: /projects/
title: "Projects"
---

## Internal Project 

### 1. Project Overview
Designed and executed a real-world OT security research project to simulate critical OWASP Top 10 attacks on an industrial testbed, followed by deploying detection mechanisms. Collaborated with interns to analyze attack patterns and develop mitigations.  


### 2. **Tools & Technologies used:**  
- *Testbed:*  
    - Real PLC
    - HMI
    - Industrial Gateway
    - FortiSwitch
    - Simulated Water Control System (e.g., CORE)  
The testbed architecture is shown in [Testbed]({{ site.baseurl }}/assets/images/testbed.png)
- *Attacks Implemented:*
    - Insider Threat (Access Control Manipulation)
    - Data Exfiltration (Covert Channel)
    - Denial of Service.  
- *Detection Tools:* 
    - Snort IDS

### 3. Attack Simulations
- *Insider Threat:*
    - Insider manipulates the Access Control List to grant access to outsider, and whitelists his email address for 2FA. 
    - Outsider attacker can now access the PLC remotely and modify the control logic
- *Data Exfiltration via Covert Channel:*
    - Using timing modulation, as series of bits conveying a message is transmitted from the raspberry to the outsider computer
-  *Fuzzing:*
    - Contributed to the design and execution of a fuzz testing framework to uncover zero-day vulnerabilities on industrial control systems. The test is focused on evaluating if a malicious input can corrupt system memory or reveal any logic flaw that could compromise the controller's operation
    - Designed python scripts used as protocol fuzzers
    - Hardware-in-the-Loop testing on embedded controllers
    - Analyzed crashes with GDB/Ghidra to identify eventual bugs



## SYNAPSE Cybersecurity Platform Infrastructure Setup 

### 1. Project Overview  
As the infrastructure lead for the SYNAPSE cybersecurity platform, I deployed and configured two Dell PowerEdge servers with Proxmox VE to host critical VMs and containers. I designed a secure networking architecture using an OPNsense firewall VM to manage traffic routing, filtering, and VLAN segmentation, while implementing WireGuard VPN with RBAC to enable secure remote access for project partners.

### 2. Technologies & Tools:  
- **Hardware:** Dell PowerEdge Servers
- **Virtualization:** Proxmox VE (Cluster Setup, KVM VMs, LXC Containers)
- **Networking:** OPNsense Firewall/Router, WireGuard VPN

### 3. Server Deployment & Virtualization
- Hardware Setup
    - Deployed and configured two Dell PowerEdge servers (RAID, ILO) for high availability and remote maintenance
    - Installed Proxmox VE as the hypervisor, configured storage and backup schedules
- Virtualized Environment
    - Created isolated VMs and LXC containers to host the cybersecurity platform components (SIEM, Snort IDS...)
    - Allocated resources based on workload requirements


### 4. Secure Networking & Remote Access
- Designed a DMZ architecture with OPNsense as the gateway VM, handling traffic filtering and NAT routing between VLANS
- Configured WireGuard VPN for secure remote access by project partners
- Implemented role-based access control (RBAC) for VPN users





