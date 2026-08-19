# Wazuh Labs 🔐

Hands-on cybersecurity labs exploring **Wazuh, SOC operations, threat detection, vulnerability detection, security monitoring, FIM, log analysis, Auditd, and incident investigation**.

This repository documents my practical learning journey through different security monitoring, detection, and investigation scenarios.

## 🧪 Labs

### Lab 01 — Network Detection with Nmap, Suricata & Wazuh

**Focus:** Network reconnaissance detection and SIEM monitoring.

**Tools:**

* Nmap
* Suricata
* Wazuh
* Ubuntu/WSL

**Detection Flow:**

```text
Nmap Scan
    ↓
Network Traffic
    ↓
Suricata IDS
    ↓
Security Alert
    ↓
Wazuh
    ↓
Monitoring & Investigation
```

➡️ [View Lab 01](Lab-01-Network-Detection/)

---

## 🔎 Upcoming Labs

### Lab 02 — Threat Hunting with Wazuh FIM

* File creation and modification
* File deletion
* Permission changes
* FIM alert analysis
* Threat-hunting workflow

### Lab 03 — SSH Brute-Force Detection

* SSH authentication monitoring
* Failed login detection
* Alert investigation
* Brute-force activity analysis

### Lab 04 — Auditd & Wazuh

* Linux audit monitoring
* Process and system activity
* Auditd events
* Security event analysis

### Lab 05 — Vulnerability Detection

* Vulnerability identification
* Wazuh vulnerability detection
* CVE analysis
* Security monitoring

### Future Labs

Additional areas will include:

* Custom Wazuh detection rules
* Log analysis
* Threat detection
* Security event correlation
* Incident investigation
* Additional Wazuh integrations

## 🎯 Learning Approach

**Build → Test → Detect → Investigate → Learn**

The goal is to understand not only how security tools work, but also how their telemetry can be used for practical SOC monitoring and investigation.

## ⚠️ Disclaimer

All testing documented in this repository is performed in controlled lab environments for educational and defensive security purposes. Security testing should only be performed against systems for which I have authorization.
