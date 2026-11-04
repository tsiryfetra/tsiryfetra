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

<details>
<summary><b>📧 Corporate Mail Infrastructure Lifecycle & Migration (Sahaza Group)</b></summary>
<br>
   
*   **Initial Deployment (April):** Designed and deployed a secure, centralized corporate mail server infrastructure tailored for **280 collaborators**, ensuring seamless multi-tenant internal communications.
*   **Hetzner Bare-Metal Architecture:** Maintained high-availability services and managed network routing, storage perimeters, and deliverability matrices on dedicated bare-metal infrastructure.
*   **Contabo VPS Emergency Migration:** Following critical external provider restrictions, orchestrated a rapid, end-to-end migration to a new **Contabo Cloud VPS (16 vCPU, 64GB RAM)**.
*   **Zero-Loss Execution:** Successfully transferred and re-indexed **300 active mailboxes** (including secure folders, sieve rules, configuration paths, and user data) with **0% data loss** and achieved **100% operational status in 36 hours** from initial root access.
*   **Security & Deliverability Hardening:** Enforced strict multi-layered public records, locking down **SPF hard-fail, DKIM keys, global DMARC p=reject policies, and Reverse PTR** records to neutralize identity spoofing and guarantee maximum deliverability.
  </details>

<details>
<summary><b>🛡️ Critical Disaster Recovery & Infrastructure Resilience (Sahaza Group)</b></summary>
<br>
 
*   **Incident Response:** Following a catastrophic fire that completely destroyed the corporate headquarters, led the emergency IT crisis response unit as the core technical coordinator.
*   **Emergency Infrastructure Rebuild:** Re-routed, architected, and physically rebuilt the entire localized network infrastructure, core server environment (Proxmox VE/pfSense), and localized power distributions on a temporary facility from scratch.
*   **Business Continuity:** Restored **100% of critical corporate services and remote workforce operations in under 48 hours with absolute zero data loss**, leveraging secure, automated, encrypted multi-site "bare-metal" backup architectures.
</details>

<details>
<summary><b>🤖 Sovereign AI Infrastructure & Intelligent Workflow Automation (Personal Homelab Project)</b></summary>
<br>

*   **Operational Objective:** Architected and deployed a fully offline, self-hosted Artificial Intelligence mini-lab to automate personal data processing without cloud dependency.
*   **Local AI Engine & Large Language Model:** Configured and deployed **Ollama** on local hardware to run the **Qwen 2.5 7B/14B / Qwen 3.5 9B** models locally, ensuring data privacy and execution sovereignty.
*   **Automated Workflow Engineering:** Built and orchestrated complex event-driven integration scenarios using **n8n** (advanced workflow automation tool).
*   **Intelligent Email Triage:** Interconnected n8n with personal Gmail storage via secure authentication protocols to retrieve, parse, and feed incoming communications into the local Qwen LLM for real-time sentiment analysis and categorization.
*   **Daily Multi-Channel Reporting:** Programmed scheduled automation tasks to synthesize evaluated data and push an intelligent, aggregated daily summary directly to **WhatsApp** interfaces via API routing.
*   **Result:** A production-grade, 100% private, sovereign automated triaging ecosystem proving advanced skills in workflow engineering, API integrations, and self-hosted AI infrastructures.
</details>

<details>
<summary><b>🛡️ Defensive SecOps Lab & Multi-Site Infrastructure Hardening | Ethical Hacking Projec (Sahaza Group)</b></summary>
<br>
   
*   **Operational Objective:** Built an ethical hacking simulation sandbox to continuously audit, detect vulnerabilities, and harden the multi-tenant production infrastructure across **4 physical corporate sites**.
*   **Multi-Site Production Architecture Under Assessment:** Directly responsible for the deployment, configuration, and maintenance of **7 local production servers** distributed across sites:
    *   `3 File Servers (Ubuntu Server + Samba)`: Engineered for strict identity management using Hierarchical Access Control and Role-Based Access Control (**RBAC**) frameworks.
    *   `2 Web Servers (Debian 12 + LAMP Stack)`: Hosting local corporate web development deployments and internal platforms.
    *   `2 Backup Servers (Ubuntu Server)`: Running dual-strategy resilience redundancy:
        *   *Server 1*: Automated incremental scripts with full centralized telemetry logs managed via **Webmin and cron job with bash script**.
        *   *Server 2*: Archive synchronization nodes executing a strict **30-day automated file retention and cleanup policy**.
*   **Penetration Testing & Vulnerability Assessment:** Utilized **Kali Linux** offensive security distributions and advanced network mapping/scanning utilities to perform proactive security audits (including credential checks, configuration flaws, and open port hunting) against the corporate mail, file, and web servers.
*   **Result:** Systematically eliminated architecture configuration blind spots, improved internal patch management, and significantly elevated the global security posture of the distributed multi-site network.
</details>
---

## 🏆 Professional Certifications & Continuing Education
*Click on a category to expand and verify my certificates:*

<details>
<summary><b>🛡️ Cybersecurity</b></summary>
<br>

* **La sécurité informatique et cybersécurité : Niveau avancé** (LinkedIn Learning)  
  [![LinkedIn - Verify](https://shields.io)](https://www.linkedin.com/learning/certificates/5ba1ee81d1cb0ce24bcb62dc9d3f5540add00745020f93029c1bf69ad8760390)

* **Cybersecurity with Cloud Computing** (LinkedIn Learning)  
  [![LinkedIn - Verify](https://shields.io)](https://www.linkedin.com/learning/certificates/54a827fae3576d9ac20e365edc4fd9cf77fd2c71e666f1d10512977dca121262)

* **The Cybersecurity Threat Landscape** (LinkedIn Learning)  
  [![LinkedIn - Verify](https://shields.io)](https://www.linkedin.com/learning/certificates/e0072778b0ea3f703faa6c198b29ed2d23c938dfe37bd5ffe7a5ce371be4199d)

* **Cybersecurity Awareness: Cloud Security** (LinkedIn Learning)  
  [![LinkedIn - Verify](https://shields.io)](https://www.linkedin.com/learning/certificates/504214b1e21328e3e90aea8a39b21cd73d2277ef513c02d272770a8322a5e4d1)

* **Cybersecurity Awareness: IoT Devices** (LinkedIn Learning)  
  [![LinkedIn - Verify](https://shields.io)](https://www.linkedin.com/learning/certificates/8b0243f685e428e1249f25d4e92921d1cb2b59ef324372f5a9bd237870c70a85)

* **Cybersecurity Foundations: Security Architecture** (LinkedIn Learning)  
  [![LinkedIn - Verify](https://shields.io)](https://www.linkedin.com/learning/certificates/29966e934ec02cd5ec5e21fbf3f31dc7383605a16b99d1ce78311c1a03d17f13)

* **Cybersecurity Fundamentals Associate** (OPSWAT Academy)  
  [![OPSWAT - Verify](https://shields.io)](https://learn.opswatacademy.com/certificate/zj0MIPU6qg)
</details>

<details>
<summary><b>🌐 Networking & Infrastructure</b></summary>
<br>

* **Administrateur Microsoft 365 et Google Workspace** (Vitako.mg)  
  [![Vitako - Verify](https://shields.io)](https://vitako.mg/#/attestation/VTK-2026-AB3991)

* **Administrateur systèmes et DevOps – Avancé** (Vitako.mg)  
  [![Vitako - Verify](https://shields.io)](https://vitako.mg/#/attestation/VTK-2026-51D3D9)

* **Sécurité des Réseaux Informatiques - Badge de réussite** (Institut Mines-Télécom / FUN-MOOC)  
  [![FUN MOOC - Verify](https://shields.io)](https://openbadgefactory.com/obv3/credentials/588ac85ace7bae29794cfad373b7c392abddad88)

* **Networking and Administration Fundamentals** (LinkedIn Learning)  
  [![LinkedIn - Verify](https://shields.io)](https://www.linkedin.com/learning/certificates/1774bf99e3253912d94334f5da4f0dd27aad9cbc838367dc0ba5edf09f323639)

* **Networking Foundations: IP Addressing** (LinkedIn Learning)  
  [![LinkedIn - Verify](https://shields.io)](https://www.linkedin.com/learning/certificates/2f99f9f06e44777bacc93a32d2794e89c1270db51361fa48841d8a87c966bd4c)

* **Networking Foundations: Networking Basics** (LinkedIn Learning)  
  [![LinkedIn - Verify](https://shields.io)](https://www.linkedin.com/learning/certificates/e9def3dd565f6d1fe178b0d31acddc9e640c578d2202b999e922ee91374453d2)
</details>

<details>
<summary><b>🪟 Microsoft & Identity Management (IAM)</b></summary>
<br>

* **Server Administration Essential Training** (LinkedIn Learning)  
  [![LinkedIn - Verify](https://shields.io)](https://www.linkedin.com/learning/certificates/16489f71bf88fe90c7b0ae2d761429b2e65c146b89e93bd527e9e80142b1c633)

* **Windows Server 2019 Essential Training** (LinkedIn Learning)  
  [![LinkedIn - Verify](https://shields.io)](https://www.linkedin.com/learning/certificates/e4fbff238ff936ee016e4952d8e17dabb6a244b08aff73bb7397143503f05bd3)

* **Azure Administration Essential Training** (LinkedIn Learning)  
  [![LinkedIn - Verify](https://shields.io)](https://www.linkedin.com/learning/certificates/aae672302c5b847d7e40beab78e9713ce84c5af1a77b378d2a733a2e039c3cbf)

* **Introduction to Identity and Access Management** (LinkedIn Learning)  
  [![LinkedIn - Verify](https://shields.io)](https://www.linkedin.com/learning/certificates/651908f5fa279b026a337ec49a335f8be4bfe28434f7874f5d12b88399333168)

* **Microsoft Defender for Endpoint: Securing and Protecting Devices** (LinkedIn Learning)  
  [![LinkedIn - Verify](https://shields.io)](https://www.linkedin.com/learning/certificates/e92e9b4bf22cefecdcd761d3896fdaf3ddf667f9e8aa80b6ad5177bae9d0cd6f)
</details>

<details>
<summary><b>☁️ Cloud Infrastructure (AWS) & Virtualization</b></summary>
<br>

* **AWS Essential Training for Architects** (LinkedIn Learning)  
  [![LinkedIn - Verify](https://shields.io)](https://www.linkedin.com/learning/certificates/01ee455ebbdee1d7b73dcf1a230c2948aef8439523015e440b3669acfacf1658)

* **Amazon Web Services Machine Learning Essential** (LinkedIn Learning)  
  [![LinkedIn - Verify](https://shields.io)](https://www.linkedin.com/learning/certificates/6a88a6ecfa4345d998f3998f81d70b764709b90cc66f734579c4c4d7c2b37e5e)

* **Learning Virtualization** (LinkedIn Learning)  
  [![LinkedIn - Verify](https://shields.io)](https://www.linkedin.com/learning/certificates/0af86a617cec5c7c640b4199cc1a87aa7795bc28d9e524f936935d4e14fbe5f6)

* **Computer Science Principles: Digital Information** (LinkedIn Learning)  
  [![LinkedIn - Verify](https://shields.io)](https://www.linkedin.com/learning/certificates/56b388ba80e0e5908c16a5999483b8dd0c37f337e5dd59a371b20eb966978cb5)

* **Computer Science Principles: The Internet** (LinkedIn Learning)  
  [![LinkedIn - Verify](https://shields.io)](https://www.linkedin.com/learning/certificates/b29f3c3ff6b64dd7aaf3e32f9ab920dd7c2d2d72ec72ebe5d0d1e54e4b917b4a)
</details>

<details>
<summary><b>🐍 Programming & Scripting</b></summary>
<br>

* **Python for Non-Programmers** (LinkedIn Learning)  
  [![LinkedIn - Verify](https://shields.io)](https://www.linkedin.com/learning/certificates/e6fd1aeec2eabfe688467d9c3d9786c1459227a278437a2c789b3b97dde8f860)

* **PowerShell: Automating Administration** (LinkedIn Learning)  
  [![LinkedIn - Verify](https://shields.io)](https://www.linkedin.com/learning/certificates/2365435ebda6f3726822477d8ff8a5edca66bca5b6c778cbcf15fc6220d00cf4)

* **Learning PowerShell** (LinkedIn Learning)  
  [![LinkedIn - Verify](https://shields.io)](https://www.linkedin.com/learning/certificates/a9f556ccf35b7d80047ba7e72baf68a843e2a5091edbbd39a8a1284dfb439da3)
</details>

<details>
<summary><b>📊 Project Management & Agile Tools</b></summary>
<br>

* **Agile Project Management with Jira Cloud: 1 Projects, Boards, and Issues** (LinkedIn Learning)  
  [![LinkedIn - Verify](https://shields.io)](https://www.linkedin.com/learning/certificates/154583c18a80cdfae5e754ede5cb70d6094ed4d66ace9c1d70160f6c5d4679a8)

* **Agile Project Management with Jira Cloud: 2 Lean and Agile Processes** (LinkedIn Learning)  
  [![LinkedIn - Verify](https://shields.io)](https://www.linkedin.com/learning/certificates/5f1b87009aa751e77d24baa6a8836951285bf31079f47e2b1cc3d105376e7f00)

* **Agile Project Management with Jira Cloud: 3 Advanced Topics** (LinkedIn Learning)  
  [![LinkedIn - Verify](https://shields.io)](https://www.linkedin.com/learning/certificates/f2895310aca77517a96b9eafe784722c30cb559c48844938155ba9a9fb202d6f)
</details>

<details>
<summary><b>☁️ Microsoft Learn</b></summary>

### 🛡️ Sécurité, Conformité & Gestion des Identités (Microsoft Learn)

* **Administrer l'identité et l'authentification des appareils (Microsoft Entra ID)**  
  [![Microsoft - Verify](https://shields.io)](https://learn.microsoft.com/api/achievements/share/fr-fr/RAKOTOARIMINOTsiryFetra-1696/WMAKMKWN?sharingId=632E5C59E45996DB)
*   **Décrire les fonctionnalités de base de Copilot de sécurité Microsoft**  
    [![Microsoft - Verify](https://shields.io)](https://learn.microsoft.com/api/achievements/share/fr-fr/RAKOTOARIMINOTsiryFetra-1696/P58FWRB4?sharingId=632E5C59E45996DB)
*   **Explorer l'identité dans Microsoft Entra ID**  
    [![Microsoft - Verify](https://shields.io)](https://learn.microsoft.com/api/achievements/share/fr-fr/RAKOTOARIMINOTsiryFetra-1696/UY7FF753?sharingId=632E5C59E45996DB)
*   **Créer, configurer et gérer des identités**  
    [![Microsoft - Verify](https://shields.io)](https://learn.microsoft.com/api/achievements/share/fr-fr/RAKOTOARIMINOTsiryFetra-1696/WZMAFSLN?sharingId=632E5C59E45996DB)
*   **Contrôler l'accès à vos API avec Gestion des API Azure**  
    [![Microsoft - Verify](https://shields.io)](https://learn.microsoft.com/api/achievements/share/fr-fr/RAKOTOARIMINOTsiryFetra-1696/N2QAWW9F?sharingId=632E5C59E45996DB)
*   **Décrire les fonctionnalités de protection contre les cyberattaques de Microsoft**  
    [![Microsoft - Verify](https://shields.io)](https://learn.microsoft.com/api/achievements/share/fr-fr/RAKOTOARIMINOTsiryFetra-1696/XPZFCLPY?sharingId=632E5C59E45996DB)
*   **Décrire les fonctionnalités de gestion de la sécurité de Microsoft**  
    [![Microsoft - Verify](https://shields.io)](https://learn.microsoft.com/api/achievements/share/fr-fr/RAKOTOARIMINOTsiryFetra-1696/8VX58VNW?sharingId=632E5C59E45996DB)

### ☁️ Fondamentaux du Cloud & Expériences Connectées (Microsoft Learn)
*   **Décrire les types de services cloud**  
    [![Microsoft - Verify](https://shields.io)](https://learn.microsoft.com/api/achievements/share/fr-fr/RAKOTOARIMINOTsiryFetra-1696/3RPDJ8VH?sharingId=632E5C59E45996DB)
*   **Décrire les avantages de l'utilisation des services cloud**  
    [![Microsoft - Verify](https://shields.io)](https://learn.microsoft.com/api/achievements/share/fr-fr/RAKOTOARIMINOTsiryFetra-1696/UYEBYPZ3?sharingId=632E5C59E45996DB)
*   **Décrire le cloud computing**  
    [![Microsoft - Verify](https://shields.io)](https://learn.microsoft.com/api/achievements/share/fr-fr/RAKOTOARIMINOTsiryFetra-1696/9XQVHV7U?sharingId=632E5C59E45996DB)
*   **Décrire les expériences intégrées de Microsoft 365**  
    [![Microsoft - Verify](https://shields.io)](https://learn.microsoft.com/api/achievements/share/fr-fr/RAKOTOARIMINOTsiryFetra-1696/9XQ2CEYU?sharingId=632E5C59E45996DB)
*   **Décrire les fonctionnalités de gestion des fonctionnalités d'entreprise de M365**  
    [![Microsoft - Verify](https://shields.io)](https://learn.microsoft.com/api/achievements/share/fr-fr/RAKOTOARIMINOTsiryFetra-1696/87K7QUEW?sharingId=632E5C59E45996DB)
*   **Optimiser votre investissement dans Microsoft 365**  
    [![Microsoft - Verify](https://shields.io)](https://learn.microsoft.com/api/achievements/share/fr-fr/RAKOTOARIMINOTsiryFetra-1696/HA4AU978?sharingId=632E5C59E45996DB)

### 📊 Modernisation, Collaboration & Productivité (Microsoft Learn)
*   **Décrire les fonctionnalités de productivité de Microsoft 365**  
    [![Microsoft - Verify](https://shields.io)](https://learn.microsoft.com/api/achievements/share/fr-fr/RAKOTOARIMINOTsiryFetra-1696/3RPRP7VH?sharingId=632E5C59E45996DB)
*   **Décrire les fonctionnalités de travail en équipe de Microsoft 365**  
    [![Microsoft - Verify](https://shields.io)](https://learn.microsoft.com/api/achievements/share/fr-fr/RAKOTOARIMINOTsiryFetra-1696/VD9JC5ZM?sharingId=632E5C59E45996DB)
*   **Analyse des données d'entreprise avec Microsoft Purview**  
    [![Microsoft - Verify](https://shields.io)](https://learn.microsoft.com/api/achievements/share/fr-fr/RAKOTOARIMINOTsiryFetra-1696/WZBSYCXN?sharingId=632E5C59E45996DB)
*   **Étendre Microsoft 365 avec Copilot**  
    [![Microsoft - Verify](https://shields.io)](https://learn.microsoft.com/api/achievements/share/fr-fr/RAKOTOARIMINOTsiryFetra-1696/HA2ZA378?sharingId=632E5C59E45996DB)

*   **Principes de base de Microsoft Azure : description des concepts du cloud**  
    [![Microsoft - Verify](https://shields.io)](https://learn.microsoft.com/api/achievements/share/fr-fr/RAKOTOARIMINOTsiryFetra-1696/P56TT624?sharingId=632E5C59E45996DB)
*   **AZ-104 : Prérequis pour les administrateurs Azure**  
    [![Microsoft - Verify](https://shields.io)](https://learn.microsoft.com/api/achievements/share/fr-fr/RAKOTOARIMINOTsiryFetra-1696/N2D2PHKF?sharingId=632E5C59E45996DB)

</details> 

<details>
<summary><b>🗣️ Languages & Professional Communication</b></summary>
<br>

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
    </details>

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


