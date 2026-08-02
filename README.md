# FUTURE_CS_01

> **Future Interns – Cyber Security Internship**
>
> **Task 1:** Reconnaissance & Passive Security Assessment using **Nmap** and **OWASP ZAP**

![Nmap](https://img.shields.io/badge/Nmap-Network%20Scanning-2E8B57?style=flat-square)
![OWASP ZAP](https://img.shields.io/badge/OWASP-ZAP-00549E?style=flat-square)
![OWASP Juice Shop](https://img.shields.io/badge/Target-OWASP%20Juice%20Shop-orange?style=flat-square)
![GitHub](https://img.shields.io/badge/GitHub-Repository-black?style=flat-square)

---

## 📌 Overview

This repository contains the deliverables for **Task 1** of the **Future Interns Cyber Security Internship**.

The objective was to perform **basic reconnaissance** and a **passive security assessment** against the intentionally vulnerable **OWASP Juice Shop** application running in a controlled local environment.

---

## 🎯 Objective

- Deploy OWASP Juice Shop locally
- Discover exposed services using Nmap
- Perform passive security analysis with OWASP ZAP
- Identify common security misconfigurations
- Generate and document the assessment report

---

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| **Nmap** | Network & Service Discovery |
| **OWASP ZAP** | Passive Web Security Assessment |
| **OWASP Juice Shop** | Target Web Application |
| **Git** | Version Control |
| **GitHub** | Repository Hosting |

---

## 🔍 Assessment Workflow

```
Deploy Target
      │
      ▼
Service Discovery (Nmap)
      │
      ▼
Passive Assessment (OWASP ZAP)
      │
      ▼
Review Findings
      │
      ▼
Generate HTML Report
      │
      ▼
Documentation
```

---

## 🚨 Key Findings

The passive assessment identified several security observations including:

- Missing Content Security Policy (CSP)
- Missing Anti-Clickjacking Header
- Missing X-Content-Type-Options Header
- Information Disclosure
- Session Related Findings
- Security Header Misconfigurations

---

## 📂 Repository Structure

```text
FUTURE_CS_01/
│
├── juice-shop/          # OWASP Juice Shop application
├── nmap/                # Nmap scan results
├── report/              # OWASP ZAP HTML Report
├── screenshots/         # Task screenshots
└── README.md
```

---

## 📄 Reports

- **Nmap Service Scan:** `nmap/`
- **OWASP ZAP HTML Report:** `report/`

---

## 📸 Screenshots

Screenshots demonstrating the setup, reconnaissance, passive scan, and generated reports are available in the **screenshots/** directory.

---

## ⚠️ Disclaimer

This assessment was performed **only** against the intentionally vulnerable **OWASP Juice Shop** application in a **controlled local environment** for educational and internship purposes.

---
<div align="center">

## 👨‍💻 Author

**Bloch**

Cyber Security Enthusiast • Aspiring Red Teamer

GitHub: https://github.com/LAISULLAH

</div>
*Cyber Security Enthusiast • Aspiring Red Teamer*

</div>
