# SOC/NOC Bootcamp Guide

Welcome to the **SOC/NOC Bootcamp Guide** 🚀  
This repository is both my personal learning path and a **public guide** for anyone who wants to follow the same journey into cybersecurity operations and network security.

---

## 🎯 Goals
- Learn fundamentals of networking and security.
- Practice with real labs (Packet Tracer, Snort, Wazuh).
- Automate tasks with Python and PowerShell.
- Build analytical and reporting skills for SOC/NOC roles.
- Share reproducible labs and exercises for the community.

---

## 📘 How to Use This Repository
1. Navigate through the `modules/` folders.
2. Each module contains:
   - **Theory** → concepts explained in simple terms.
   - **Practice** → labs with `.pkt`, configs, or scripts.
   - **Automation** → scripts to simplify tasks.
   - **Evidence** → my own labs, which you can replicate.
3. Follow the `checklist.md` to track progress.
4. Use the Wiki for a step-by-step learning path.

---

## 📂 Repository Structure
soc-noc-bootcamp-guide/
│
├── README.md
├── checklist.md
├── modules/
│   ├── module1_networks/
│   │   ├── theory.md
│   │   ├── practice.md
│   │   └── evidences/
│   │       ├── topology_basic.pkt
│   │       ├── ping_traceroute.pkt
│   │       └── README.md
│   ├── module2_alerts_tickets/
│   ├── module3_monitoring_reporting/
│   ├── module4_identity_access/
│   ├── module5_implementations/
│   └── module6_analytics_communication/
└── scripts/   # automation examples (Python, PowerShell, Bash)


---

## 📘 Modules
- **Module 1: Networks Fundamentals** → OSI, TCP/IP, Packet Tracer labs.
- **Module 2: Alerts & Tickets** → SOC workflow, triage simulation.
- **Module 3: Monitoring & Reporting** → DLP, EDR, dashboards.
- **Module 4: Identity & Access** → Azure AD, IAM, Zero Trust.
- **Module 5: Implementations & PoC** → Snort, Wazuh, proof of concept.
- **Module 6: Analytical & Communication Skills** → root cause analysis, executive reports.

---

## 🧪 Labs
All labs are stored in `evidences/` folders.  
You can download `.pkt` files (Packet Tracer), configs, and scripts to reproduce the exercises.

Example:

Lab: Basic Network Topology
Objective: Understand IP addressing and connectivity.
Steps:
1. Open `topology_basic.pkt` in Packet Tracer.
2. Assign IPs: PC1 → 192.168.1.10, PC2 → 192.168.1.20.
3. Test connectivity with `ping`.
Expected Result: Both PCs should communicate successfully.

##⚙️ Automation
This bootcamp includes automation examples:

PowerShell → create users in Azure AD.

Python → analyze logs and generate reports.

Bash → restart services like Snort automatically.

Scripts are stored in the scripts/ folder.

##🤝 Contribution
This repository is open for learning.
If you want to add your own labs or improvements:

Fork the repo.

Create a branch (feature/moduleX).

Submit a pull request.

##📚 Learning Path
For a guided experience, check the Wiki section:

Getting Started

Module by Module Guide

Automation Scripts

Recommended Resources

