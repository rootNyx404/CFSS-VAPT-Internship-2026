# 🛡️ CFSS Internship 2026 - End-to-End VAPT Simulation

![CFSS](https://img.shields.io/badge/CFSS-Internship%202026-blue)
![VAPT](https://img.shields.io/badge/Domain-VAPT-red)
![TryHackMe](https://img.shields.io/badge/Platform-TryHackMe-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 🎯 Project Overview

This repository contains my work completed as part of the **CFSS Global Internship Program 2026**.

### Project Title
**The Vulnerability Report Card – End-to-End VAPT Simulation**

The objective of this project was to perform a structured Vulnerability Assessment and Penetration Testing (VAPT) exercise in a controlled lab environment using TryHackMe.

---

## 👨‍💻 Internship Details

| Field | Details |
|---------|---------|
| Organization | CFSS (Cyber Security & Forensics Services) |
| Program | CFSS Global Internship 2026 |
| Domain | Ethical Hacking & Penetration Testing |
| Platform | TryHackMe |
| Target Machine | Blue |
| Operating System | Parrot Security OS |

---

## 🛠️ Tools Used

- Nmap
- Metasploit Framework
- Searchsploit
- SMB Enumeration
- TryHackMe
- Parrot Security OS

---

## 🔄 VAPT Methodology

```text
Reconnaissance
      ↓
Scanning
      ↓
Enumeration
      ↓
Vulnerability Research
      ↓
Validation
      ↓
Risk Assessment
      ↓
Reporting
```

## 🌐 Open Ports Discovered

| Port | Service |
|------|----------|
| 135 | MSRPC |
| 139 | NetBIOS |
| 445 | SMB |
| 3389 | RDP |
| 49152 | RPC |
| 49153 | RPC |
| 49154 | RPC |
| 49160 | RPC |

---

## 🖥️ Target Information

| Property | Value |
|-----------|--------|
| Hostname | JON-PC |
| Operating System | Windows 7 Professional SP1 |
| Architecture | x64 |
| Workgroup | WORKGROUP |

---

## 🔍 Vulnerability Research

### Identified Vulnerability

**MS17-010 (EternalBlue)**

Affected Service:

```text
TCP 445 - SMB
```

Research was performed using:

- Searchsploit
- Metasploit
- SMB Enumeration

---

## ✅ Vulnerability Validation

Metasploit vulnerability scanner results:

```text
[+] Host is likely VULNERABLE to MS17-010!
Windows 7 Professional 7601 Service Pack 1 x64
```

### Risk Level

🔴 Critical

---

## 📊 Risk Assessment

| Vulnerability | Severity |
|---------------|----------|
| MS17-010 EternalBlue | 🔴 Critical |
| SMB Exposure | 🟠 High |
| Windows 7 Legacy System | 🟠 High |
| Exposed RDP Service | 🟡 Medium |

---

## 🛡️ Recommendations

- Apply Microsoft security patches immediately
- Disable SMBv1 where possible
- Restrict SMB access through firewall rules
- Restrict Remote Desktop access
- Implement network segmentation
- Conduct regular vulnerability assessments
- Enable continuous security monitoring

---

## 📂 Repository Structure

```text
CFSS-VAPT-Internship-2026/
│
├── README.md
├── VAPT_Report.pdf
│
└── Screenshots/
    ├── Blue_Room_Completion.png
    ├── Nmap_Scan.png
    ├── SMB_OS_Discovery.png
    ├── Searchsploit_MS17-010.png
    ├── MS17-010_Vulnerability_Check.png
    └── EternalBlue_Module_Search.png
```

---

## 📸 Evidence Included

- ✅ Blue Room Completion
- ✅ Nmap Scan Results
- ✅ SMB OS Discovery
- ✅ Searchsploit Research
- ✅ MS17-010 Validation
- ✅ EternalBlue Module Discovery

---

## ⚠️ Disclaimer

This project was conducted strictly within an authorized educational environment provided by TryHackMe as part of the CFSS Global Internship Program 2026.

The information contained in this repository is intended solely for educational, research, and defensive cybersecurity purposes.

---

## 👤 Author

**Arup Halder**

CFSS Global Internship Program 2026

Cyber Security | VAPT | Ethical Hacking | Network Security

---

⭐ Thank you for visiting this repository.
