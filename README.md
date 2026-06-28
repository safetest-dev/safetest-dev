# 🔐 Michael Anggi G.A.

**Programming | Software/Firmware Security | Reverse Engineering | Binary Analysis | Malware Analysis | SOC**

---

## 🧠 Profile

Computer and Network researcher specializing in **low-level system analysis, binary exploitation, and malware reverse engineering**, with a growing focus on **SOC operations and detection engineering**.

This portfolio demonstrates a **structured, hands-on progression of offensive *and* defensive security capabilities**, covering:

* **Reverse engineering of real binaries**
* **Memory corruption exploitation**
* **Malware behavior reconstruction**
* **Control flow manipulation on real-world software**
* **SIEM-based threat detection, alert triage, and incident response**

With **10+ years of engineering experience in the oil & gas industry**, I bring:

* **Strong analytical thinking**
* **System-level modeling mindset**
* **Experience working in high-risk, high-impact environments**

into cybersecurity practice.

---

## ⚔️ Core Capabilities

### 🧠 Reverse Engineering

* Static & dynamic analysis of ELF binaries using **radare2**
* **Control flow reconstruction** and execution tracing
* Pseudo-code decompilation via **r2ghidra**
* Binary logic validation & behavioral modeling

---

### 🔐 Binary Analysis & Exploitation

* **Stack buffer overflow exploitation** (ret2win, ret2libc, ROP chains)
* **Stack canary bypass** via format string vulnerabilities
* **ASLR, NX, PIE bypass** using information disclosure
* Exploit development using **Python (pwntools)**

---

### 🦠 Malware Analysis

* Full **behavioral reconstruction of ELF malware**
* **C2 communication analysis** (AES-128-CBC, Base64, HTTP)
* Credential harvesting & system reconnaissance techniques
* **YARA rule creation** and IoC extraction

---

### 🛡️ SOC / Blue Team

* **SIEM-based detection & threat hunting** with **Wazuh**
* **Alert triage and severity escalation analysis** (rule correlation, level scoring)
* **Log decoding & evidence extraction** from raw `sshd` / `journald` sources
* **MITRE ATT&CK mapping** of observed activity (Credential Access, Lateral Movement)
* **Compliance-aware reporting** (PCI-DSS, HIPAA, NIST 800-53, GDPR, TSC)
* **Incident response & containment** recommendations (IOC blocking, hardening, hunting pivots)

---

## 🧩 Research Domains

* **Memory Corruption & Control Flow Hijacking**
* **Mitigation Bypass Techniques**
* **Command & Control (C2) Analysis**
* **Low-Level System Behavior**
* **Threat Detection & Security Monitoring**
* **Credential-Access & Brute-Force Detection**

---

## 🚀 Portfolio Breakdown

### 🔴 Reverse Engineering

📂 https://github.com/safetest-dev/01_Reverse_Engineering

Structured lab series focusing on **binary analysis and execution flow understanding**.

**Highlighted Work:**

* Secure boot validation bypass
* Encoded authentication reversal
* Algorithmic verification analysis
* XOR-based data decoding
* **Control flow manipulation on real-world software (Notepad++ installer)**
  → Demonstrates **limitations of single-point integrity checks under binary patching**

---

### 🔐 Binary Exploitation

📂 https://github.com/safetest-dev/02_Binary_Exploitation

Hands-on exploitation scenarios targeting **memory corruption vulnerabilities**.

**Highlighted Work:**

* Stack Buffer Overflow → **RIP control (ret2win)**
* Canary bypass via **format string leak**
* ret2libc exploitation with **ASLR bypass**
* Format string exploitation → **memory disclosure (PIE bypass)**
  *(including web-based vector using Burp Suite)*

---

### 🦠 Malware Analysis

📂 https://github.com/safetest-dev/03_Malware_Analysis

Analysis of **real-world inspired Linux malware samples**, focusing on behavior and detection.

**Highlighted Work:**

* Disk exhaustion malware (**file I/O abuse + anti-debugging**)
* C2 telemetry agent:

  * AES + Base64 encoding
  * HTTP beaconing
* Credential & system data exfiltration:

  * system fingerprinting (`uname`)
  * environment harvesting
  * bash history extraction

---

### 🛡️ SOC / Blue Team

📂 https://github.com/safetest-dev/04_SOC

Defensive lab series focusing on **detection engineering, alert triage, and incident response** using a Wazuh SIEM stack.

**Highlighted Work:**

* **SOC-01 — SSH Invalid-User / Brute-Force Detection**
  → Detected and triaged an SSH credential-access attempt against a monitored Linux host
  → Correlated low-severity invalid-user events (rule 5710) into a level-10 brute-force escalation (rule 2502)
  → Decoded raw `sshd-session` logs to extract attacker IP and target username as evidence
  → Mapped to **MITRE ATT&CK T1110.001 (Password Guessing)** and **T1021.004 (SSH)**
  → Produced containment and hardening recommendations (IP blocking, key-based auth, exposure reduction)

---

## 🔬 Methodology

My approach to security research:

1. **Static Analysis** → binary structure, strings, function mapping
2. **Dynamic Analysis** → runtime behavior, syscall tracing
3. **Root Cause Analysis** → vulnerability identification
4. **Exploitation / Reconstruction** → proof-of-concept development
5. **Detection & Defense** → SIEM detection, alert triage, IoC extraction, YARA rules
6. **Incident Response** → containment, hardening, and threat-hunting follow-up

---

## 🛠️ Tools & Environment

* GDB / pwndbg
* Radare2 (r2), r2ghidra
* pwntools
* Python
* strace, ltrace
* YARA
* **Wazuh (SIEM / XDR)** — detection, threat hunting, alert triage
* **MITRE ATT&CK** — adversary technique mapping
* Linux (Arch / BlackArch)

---

## 🎯 Career Direction

Currently transitioning into cybersecurity roles with focus on:

* **Reverse Engineer**
* **Security Researcher**
* **Malware Analyst**
* **Offensive Security Engineer**
* **SOC Analyst / Detection Engineer (Blue Team)**

---

## 🌍 Availability

* Open to **remote opportunities**
* Open to **contract / freelance / full-time roles**

---

## 📫 Contact

* GitHub: https://github.com/safetest-dev
* Email: [safetestmail@proton.me](mailto:safetestmail@proton.me)

---
