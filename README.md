
https://github.com/user-attachments/assets/9c855b97-28c2-4a8e-a873-6530b3e51c6b

# 🛡️ DIANO Autonomous Security Grid v4.0

DIANO is an advanced, AI-driven **Autonomous Intrusion Response System** designed to protect enterprise networks from malicious threats. Powered by a trained BigML neural network model, the system continuously monitors live network traffic, detects anomalies with high confidence, and executes zero-touch mitigation countermeasures.

## 🚀 Core Features
* **98.81% AI Detection Accuracy:** Leverages a pre-trained specific model (`diano_model`) to distinguish between legitimate traffic and malicious threats.
* **Zero-Touch Automated Mitigation:** Instantly blocks attacker IPs and configures security rules upon threat detection without human intervention.
* **Intelligent Live Dashboard:** Built with a premium, modern, clean user interface inspired by world-class applications, providing visual clarity at a glance.
* **Tamper-Proof Audit Logging:** Maintains a chronological security vault log (`diano_security_vault.log`) of all security actions taken.
* **Acoustic Alert Engine:** Triggers localized acoustic alarms to notify system administrators during active breaches.

## 📦 System Architecture
The repository contains the core components required to run the engine:
1. `main.py` - The primary security engine core logic and user interface.
2. `diano_model.` - The trained machine learning model containing security heuristics.

## 💻 How It Works (For Enterprises)
1. The application runs autonomously in the background as a portable solution.
2. When a cyber threat (e.g., DDoS or Brute-Force) is detected, the AI engine triggers the **Autonomous Breach Defense mode**.
3. After isolating the threat and cooling down the node, the shield automatically resets to its optimal active state.
