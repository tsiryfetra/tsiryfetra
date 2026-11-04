# 👋 Hi, I'm Tsiry Fetra

### 🖥️ Systems, Networks, Identity & Security Administrator
Welcome to my professional development repository. This space centralizes all valid certifications, advanced training, and continuing professional development (CPD) credentials earned throughout my career. It acts as an official appendix to my application for senior IT operations and infrastructure leadership roles.

---

## 🚀 Realized Production Projects

<details>
<summary><b>🌐 Secure Corporate Infrastructure Deployment (120 Users / 3-Shift Operations) — May 2026 (Sahaza Group)</b></summary>
<br>
   
*   **Operational Objective:** Architected and deployed an infrastructure designed for 24/7 total availability, supporting **120 active users** across 3 operational shifts (AM-PM-NIGHT).
*   **Virtualization & High Availability:** Implemented a resilient hypervisor cluster running two Dell servers under **Proxmox VE** to ensure automatic failover and redundancy for critical services.
*   **Perimeter Security & Multi-WAN:** Deployed a **pfSense** security gateway managing dual internet sources (**Telma Fiber Optique & Starlink Satellite**) with automated failover and strict inbound/outbound packet filtering.
*   **Advanced Network Segmentation (HP Manageable Switching):** Engineered a granular **VLAN** topology to isolate broadcast domains and reinforce security perimeters:
    *   `VLAN 10 (Management)`: Dedicated equipment administration and hardware monitoring isolation.
    *   `VLAN 20 (Users)`: Specialized subnet managing **40 secure workstations** running Windows 11 Pro with dedicated DHCP mapping.
    *   `VLAN 30 (Servers)`: Centralized core hosting **Active Directory (Windows Server 2019)** seamlessly interconnected with **Ubuntu Server 24.04 LTS** file shares via Samba, SSSD, and Winbind.
    *   `VLAN 40 (SIEM/SOC)`: Isolated telemetry zone running security collectors under Debian 12.
    *   `VLAN 50 (Backup)`: Isolated network segment for automated historical data archiving.
*   **Security Operations (SOC) & Telemetry:** Integrated **Wazuh SIEM** for active host intrusion detection and log analysis, paired with real-time performance dashboards built on **Prometheus & Grafana**.
*   **Result:** A production-ready, highly resilient corporate infrastructure capable of absorbing complete ISP link failures transparently with centralized access control using AD credentials.
  </details>

### 📧 Corporate Mail Infrastructure Lifecycle & Migration (Sahaza Group)
*   **Initial Deployment (April):** Designed and deployed a secure, centralized corporate mail server infrastructure tailored for **280 collaborators**, ensuring seamless multi-tenant internal communications.
*   **Hetzner Bare-Metal Architecture:** Maintained high-availability services and managed network routing, storage perimeters, and deliverability matrices on dedicated bare-metal infrastructure.
*   **Contabo VPS Emergency Migration:** Following critical external provider restrictions, orchestrated a rapid, end-to-end migration to a new **Contabo Cloud VPS (16 vCPU, 64GB RAM)**.
*   **Zero-Loss Execution:** Successfully transferred and re-indexed **300 active mailboxes** (including secure folders, sieve rules, configuration paths, and user data) with **0% data loss** and achieved **100% operational status in 36 hours** from initial root access.
*   **Security & Deliverability Hardening:** Enforced strict multi-layered public records, locking down **SPF hard-fail, DKIM keys, global DMARC p=reject policies, and Reverse PTR** records to neutralize identity spoofing and guarantee maximum deliverability.

### 🛡️ Critical Disaster Recovery & Infrastructure Resilience (Sahaza Group)
*   **Incident Response:** Following a catastrophic fire that completely destroyed the corporate headquarters, led the emergency IT crisis response unit as the core technical coordinator.
*   **Emergency Infrastructure Rebuild:** Re-routed, architected, and physically rebuilt the entire localized network infrastructure, core server environment (Proxmox VE/pfSense), and localized power distributions on a temporary facility from scratch.
*   **Business Continuity:** Restored **100% of critical corporate services and remote workforce operations in under 48 hours with absolute zero data loss**, leveraging secure, automated, encrypted multi-site "bare-metal" backup architectures.

---

## 🏆 Professional Certifications & Continuing Education
*Click on a category to expand and verify my certificates:*

<details>
<summary><b>🛡️ Cybersecurity & Network Security</b></summary>
<br>

* **Sécurité des Réseaux Informatiques - Badge de réussite** (Institut Mines-Télécom / FUN-MOOC)  
  [![FUN MOOC - Verify](https://shields.io)](https://openbadgefactory.com)

* **Administrateur systèmes et DevOps – Avancé** (Vitako.mg)  
  [![Vitako - Verify](https://shields.io)](https://vitako.mg)

* **La sécurité informatique et cybersécurité : Niveau avancé** (LinkedIn Learning)  
  [![LinkedIn - Verify](https://shields.io)](https://linkedin.com)

* **Cybersecurity with Cloud Computing** (LinkedIn Learning)  
  [![LinkedIn - Verify](https://shields.io)](https://linkedin.com)

* **The Cybersecurity Threat Landscape** (LinkedIn Learning)  
  [![LinkedIn - Verify](https://shields.io)](https://linkedin.com)

* **Cybersecurity Awareness: Cloud Security** (LinkedIn Learning)  
  [![LinkedIn - Verify](https://shields.io)](https://linkedin.com)

* **Cybersecurity Awareness: IoT Devices** (LinkedIn Learning)  
  [![LinkedIn - Verify](https://shields.io)](https://linkedin.com)

* **Cybersecurity Foundations: Security Architecture** (LinkedIn Learning)  
  [![LinkedIn - Verify](https://shields.io)](https://linkedin.com)

* **Cybersecurity Fundamentals Associate** (OPSWAT Academy)  
  [![OPSWAT - Verify](https://shields.io)](https://opswatacademy.com)
</details>

<details>
<summary><b>🪟 Microsoft, Identity Management (IAM) & Cloud Collaboration</b></summary>
<br>

* **Administrer l'identité et l'authentification des appareils** (Microsoft Entra ID)  
  [![Microsoft - Verify](https://shields.io)](https://microsoft.com)
* **Describe cloud service types** (Microsoft Learn)  
  [![Microsoft - Verify](https://shields.io)](https://microsoft.com)
* **Describe the benefits of using cloud services** (Microsoft Learn)  
  [![Microsoft - Verify](https://shields.io)](https://microsoft.com)
* **Describe cloud computing** (Microsoft Learn)  
  [![Microsoft - Verify](https://shields.io)](https://microsoft.com)
* **Describe the integrated experiences of Microsoft 365** (Microsoft Learn)  
  [![Microsoft - Verify](https://shields.io)](https://microsoft.com)
* **Describe the business management capabilities of Microsoft 365** (Microsoft Learn)  
  [![Microsoft - Verify](https://shields.io)](https://microsoft.com)
* **Optimize your Microsoft 365 investment** (Microsoft Learn)  
  [![Microsoft - Verify](https://shields.io)](https://microsoft.com)
* **Describe Microsoft 365 productivity and teamwork capabilities** (Microsoft Learn)  
  [![Microsoft - Verify](https://shields.io)](https://microsoft.com)
* **Describe Microsoft 365 teamwork capabilities** (Microsoft Learn)  
  [![Microsoft - Verify](https://shields.io)](https://microsoft.com)
* **Analyze enterprise data with Microsoft Purview** (Microsoft Learn)  
  [![Microsoft - Verify](https://shields.io)](https://microsoft.com)
* **Extend Microsoft 365 with Copilot** (Microsoft Learn)  
  [![Microsoft - Verify](https://shields.io)](https://microsoft.com)
* **Describe Microsoft compliance capabilities** (Microsoft Learn)  
  [![Microsoft - Verify](https://shields.io)](https://microsoft.com)
* **Describe Microsoft 365 service and architecture concepts** (Microsoft Learn)  
  [![Microsoft - Verify](https://shields.io)](https://microsoft.com)
* **Administrateur Microsoft 365 et Google Workspace** (Vitako.mg)  
  [![Vitako - Verify](https://shields.io)](https://vitako.mg)

* **Server Administration Essential Training** (LinkedIn Learning)  
  [![LinkedIn - Verify](https://shields.io)](https://linkedin.com)
* **Windows Server 2019 Essential Training** (LinkedIn Learning)  
  [![LinkedIn - Verify](https://shields.io)](https://linkedin.com)
* **Azure Administration Essential Training** (LinkedIn Learning)  
  [![LinkedIn - Verify](https://shields.io)](https://linkedin.com)
* **Introduction to Identity and Access Management** (LinkedIn Learning)  
  [![LinkedIn - Verify](https://shields.io)](https://linkedin.com)
* **Microsoft Defender for Endpoint: Securing and Protecting Devices** (LinkedIn Learning)  
  [![LinkedIn - Verify](https://shields.io)](https://linkedin.com)
</details>
<details>
<summary><b>☁️ Cloud Infrastructure (AWS) & Virtualization</b></summary>
<br>

* **AWS Essential Training for Architects** (LinkedIn Learning)  
  [![LinkedIn - Verify](https://shields.io)](https://linkedin.com)

* **Amazon Web Services Machine Learning Essential** (LinkedIn Learning)  
  [![LinkedIn - Verify](https://shields.io)](https://linkedin.com)

* **Learning Virtualization** (LinkedIn Learning)  
  [![LinkedIn - Verify](https://shields.io)](https://linkedin.com)

* **Computer Science Principles: Digital Information** (LinkedIn Learning)  
  [![LinkedIn - Verify](https://shields.io)](https://linkedin.com)

* **Computer Science Principles: The Internet** (LinkedIn Learning)  
  [![LinkedIn - Verify](https://shields.io)](https://linkedin.com)
</details>
<details>
<summary><b>🌐 Networking & Systems Fundamentals</b></summary>
<br>

* **Networking and Administration Fundamentals** (LinkedIn Learning)  
  [![LinkedIn - Verify](https://shields.io)](https://linkedin.com)

* **Networking Foundations: IP Addressing** (LinkedIn Learning)  
  [![LinkedIn - Verify](https://shields.io)](https://linkedin.com)

* **Networking Foundations: Networking Basics** (LinkedIn Learning)  
  [![LinkedIn - Verify](https://shields.io)](https://linkedin.com)
</details>
<details>
<summary><b>🐍 Programming, Automation & Scripting</b></summary>
<br>

* **PowerShell: Automating Administration** (LinkedIn Learning)  
  [![LinkedIn - Verify](https://shields.io)](https://linkedin.com)

* **Learning PowerShell** (LinkedIn Learning)  
  [![LinkedIn - Verify](https://shields.io)](https://linkedin.com)

* **Python for Non-Programmers** (LinkedIn Learning)  
  [![LinkedIn - Verify](https://shields.io)](https://linkedin.com)
</details>

<details>
<summary><b>📊 Project Management & Agile Tools</b></summary>
<br>

* **Agile Project Management - Scrum Framework** (pm.coaching.org)  
  [![pm.coaching - Progress](https://shields.io)](https://coaching.org)

* **Agile Project Management with Jira Cloud: 1 Projects, Boards, and Issues** (LinkedIn Learning)  
  [![LinkedIn - Verify](https://shields.io)](https://linkedin.com)

* **Agile Project Management with Jira Cloud: 2 Lean and Agile Processes** (LinkedIn Learning)  
  [![LinkedIn - Verify](https://shields.io)](https://linkedin.com)

* **Agile Project Management with Jira Cloud: 3 Advanced Topics** (LinkedIn Learning)  
  [![LinkedIn - Verify](https://shields.io)](https://linkedin.com)
</details>

## 🗣️ Languages & Professional Communication

Ability to evolve seamlessly within international, intergovernmental, and multicultural work environments.

* **Malagasy :** Native language.
* **French:**  Full professional proficiency.
* **English:** Professional working proficiency.
* 
  * **English for Career Development: Interviewing for a Job** (U.S. Department of State / Parchment)  
    [![Parchment - Verify](https://shields.io)](https://parchment.com)
  * **Unlock Your English 2 (Advanced Curriculum - 80% Threshold)** (Institut Mines-Télécom / FUN-MOOC)  
    [![FUN MOOC - Verify](https://shields.io)](https://openbadgefactory.com)
  * **Unlock Your English** (Institut Mines-Télécom / FUN-MOOC)  
    [![FUN MOOC - Verify](https://shields.io)](https://openbadgefactory.com)

## 🛠️ Technical Skills Portfolio

| Domain | Technologies & Frameworks |
| :--- | :--- |
| **Security & MCO** | Netfilter/Iptables filtering, Fail2ban advanced hardening, VPN (IPsec/TLS), Wazuh SIEM, Wireshark, Nmap |
| **Sovereign Messaging** | Mailcow architecture, iRedMail, Postfix-Dovecot, Docker Compose, Delivery compliance (SPF, DKIM, DMARC, Reverse PTR) |
| **OS & Directory Services** | GNU/Linux (Debian, Ubuntu Server), Microsoft Entra ID (Azure AD), Active Directory, Apple macOS |
| **Virtualization & HA** | Proxmox VE hypervisor, VMware, Clusters & High Availability storage solutions |
| **Automation & Tooling** | Bash scripting, Cron job engineering, Jira Service Management |
| **Physical Infrastructure** | Structured network cabling, Datacenter power planning, Off-grid hybrid photovoltaic solar system sizing |

---

## 🔒 Verifiability Notice

All original digital credentials, transcripts, and official verification badges listed above are securely managed. Verifiable cryptographic records or signed documentation can be produced immediately upon institutional request.


