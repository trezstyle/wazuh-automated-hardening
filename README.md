# Wazuh Automated Hardening Lab

This project provides an automated deployment and security hardening configuration for [Wazuh](https://wazuh.com/), the open-source XDR/SIEM platform. The lab is designed to simulate a production-like security monitoring environment following **BSI IT-Grundschutz** principles focusing on continuous security, threat detection, and system hardening.

## 🚀 Project Goals
- **Automated Deployment**: Streamline installation of Wazuh Manager, Indexer, and Dashboard.
- **Security Hardening**: Implement automated hardening policies for Linux endpoints.
- **Threat Detection**: Custom rule engineering for real-time monitoring and anomaly detection.
- **Compliance Baseline**: Align logging and monitoring output with BSI security requirements.

## 📁 Repository Structure
- `documentation/`: Detailed architectural design and compliance mapping.
- `playbooks/`: Ansible playbooks for automated agent deployment.
- `wazuh_configs/`: Custom rules and decoders for specific attack scenarios.
- `dashboards/`: Exported Kibana dashboards for SIEM visualization.

## 🛠 Tech Stack
- **SIEM/XDR**: Wazuh
- **Automation**: Ansible
- **Containerization**: Docker
- **Environment**: Linux (Ubuntu/Debian)

---
*Created by Vadym Lapynin*
