# 🚨 FUTURE_CS_02: Security Incident Report – SIEM Log Analysis

This repository contains the **Cybersecurity Case Study 02** as part of the Future Interns SOC Internship. It focuses on analyzing SIEM logs, identifying suspicious user behaviors, and documenting threats, their impact, and appropriate response actions.

---

## 📌 Overview

- **Objective**: To investigate and document unusual or malicious activities using SIEM data.
- **Tools Used**: Splunk
- **Techniques**: Log analysis, threat classification, impact assessment, and remediation planning.
- **Timeline**: July 2025

---

## 🧾 Key Findings

| Time             | User   | IP Address     | Action           | Threat/Notes              | Priority |
| ---------------- | ------ | -------------- | ---------------- | ------------------------- | -------- |
| 2025-07-03 09:10 | bob    | 172.16.0.3     | malware detected | Ransomware Behavior       | High     |
| 2025-07-03 09:02 | david  | 203.0.113.77   | login failed     | Multiple failed attempts  | Medium   |
| 2025-07-03 08:42 | eve    | 172.16.0.3     | file accessed    | Suspicious file access    | Low      |

---

## 📊 Impact Assessment

### 1. Ransomware Behavior (High)
- Can cause full system or data encryption.
- May halt business operations until ransom is paid.
- Risk of data leak and permanent loss.

### 2. Multiple Failed Login Attempts (Medium)
- Indicates brute-force attack attempts.
- Weakens system’s authentication integrity.
- May lead to unauthorized access if not mitigated.

### 3. Suspicious File Access (Low)
- Could be early stage of insider threat.
- Indicates users bypassing normal workflows.
- Potential for data misuse if repeated.

---

## 🛡️ Response Actions Taken

1. Isolated the affected system (bob’s endpoint) to prevent lateral movement.
2. Reset credentials for users with failed login attempts.
3. Enabled multi-factor authentication (MFA).
4. Monitored and logged suspicious file activity from eve’s user account.
5. Conducted full malware scans on impacted assets.

---

## 🔧 Remediation Plan

To avoid future occurrences:
- Implement strict **access control policies**.
- Enforce **password complexity rules** and **account lockout mechanisms**.
- Configure **real-time threat alerting** with auto-response rules.
- Regularly update and patch all systems.
- Conduct **security awareness training** for users to prevent ransomware and phishing exploitation.

---

## 📁 Files Included

- `incident_report_future_cs02.pdf` – Full case report  
- `threat_analysis_table.md` – Tabular threat overview  
- `impact_assessment.md` – Detailed analysis  
- `response_plan.md` – Actions and remediation steps  

---

## 🧠 Author

**B Haritheertha**  
Cybersecurity Intern – Future Interns  
GitHub: [@Haritheertha](https://github.com/Haritheertha)

