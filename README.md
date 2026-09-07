# Enterprise SOC Lab & Threat Detection Simulation

## 📌 Project Overview
This project demonstrates the deployment of an enterprise-grade Security Operations Center (SOC) environment. The goal is to monitor infrastructure, detect live cyber threats, and configure automated responses using open-source SIEM/EDR tools.

## 🛠️ Technologies & Tools Used
* **SIEM / EDR:** Wazuh (Central Manager & Agents)
* **Operating Systems:** Windows Server (Active Directory), Ubuntu Linux
* **Hypervisor:** Oracle VirtualBox
* **Attack Tools:** Kali Linux (Nmap, Hydra)

## 🏗️ Lab Architecture
1. **Wazuh Manager:** Installed on a dedicated Ubuntu Server to aggregate and analyze security logs.
2. **Monitored Endpoints:** Windows Server and Ubuntu client machines configured with Wazuh Agents.
3. **Attacker Machine:** Kali Linux used to simulate real-world attacks.

## 🛡️ Use Cases & Attack Simulations
* **Use Case 1: Brute Force Attack Detection**
  * Simulated a SSH/RDP brute force attack using Hydra from Kali Linux.
  * *Result:* Wazuh generated high-severity alerts (Rule ID: 5712) in real-time.
* **Use Case 2: Automated Incident Response**
  * Configured active response scripts to automatically block the attacker's IP address upon detecting multi-failed login attempts.

## 📈 Project Deliverables & Screenshots
*(Here I will upload the screenshots of my Wazuh dashboard showing the alerts)*

