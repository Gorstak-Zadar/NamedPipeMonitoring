# 📡 NamedPipeMonitoring

> **Named Pipe Communication Monitor** - Detects malicious named pipe usage for C2 and inter-process communication.

---

## 📋 Overview

NamedPipeMonitoring monitors Windows named pipes for malicious usage including Cobalt Strike default pipes, suspicious pipe names, and C2 communication channels.

---

## 🎯 What It Detects

- 📡 **Named Pipe Creation** - New pipe monitoring
- 🎯 **Cobalt Strike Pipes** - Default CS pipe names
- ⚠️ **Suspicious Names** - Anomalous pipe patterns
- 📂 **Temp Directory Pipes** - Pipes from suspicious locations

---

## 🚀 Usage

```powershell
# Monitor named pipes
.\NamedPipeMonitoring.ps1
```

---

## 📜 License & Disclaimer

This software is for **AUTHORIZED IPC MONITORING** only.
---

## Comprehensive legal disclaimer

This project is intended for authorized defensive, administrative, research, or educational use only.

- Use only on systems, networks, and environments where you have explicit permission.
- Misuse may violate law, contracts, policy, or acceptable-use terms.
- Running security, hardening, monitoring, or response tooling can impact stability and may disrupt legitimate software.
- Validate all changes in a test environment before production use.
- This project is provided "AS IS", without warranties of any kind, including merchantability, fitness for a particular purpose, and non-infringement.
- Authors and contributors are not liable for direct or indirect damages, data loss, downtime, business interruption, legal exposure, or compliance impact.
- You are solely responsible for lawful operation, configuration choices, and compliance obligations in your jurisdiction.

---

<p align="center">
  <sub>Built with care by <strong>Gorstak</strong></sub>
</p>