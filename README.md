# 🌐 Network Traffic Analysis & Threat Detection using Wireshark

## 📌 Overview
This project simulates a SOC Analyst investigation using Wireshark to analyze network traffic and detect suspicious activities based on TryHackMe labs.

---

## 🎯 Objective
- Analyze packet captures
- Identify suspicious network behavior
- Detect potential cyber threats
- Apply SOC investigation methodology

---

## 🔍 Investigation Summary

### 🚨 1. Port Scanning (Reconnaissance)
- Multiple SYN packets sent to different ports
- Port 22 → Open | Port 21 → Closed

🧠 Assessment: Reconnaissance activity  
🔥 Severity: Medium  
🎯 SOC Action: Monitor source IP and apply rate limiting  

---

### ⚠️ 2. ARP Spoofing (MITM Attack)
- Duplicate IP mapped to multiple MAC addresses

🧠 Assessment: ARP poisoning attempt  
🔥 Severity: High  
🎯 SOC Action: Validate ARP tables and isolate attacker  

---

### 🕵️ 3. ICMP Tunneling (Data Exfiltration)
- Large ICMP packets (>1000 bytes)

🧠 Assessment: Possible covert data exfiltration  
🔥 Severity: High  
🎯 SOC Action: Restrict ICMP traffic  

---

### 🌐 4. HTTP Exploit Attempt
- Suspicious payload detected (e.g. jndi)

🧠 Assessment: Possible web exploitation attempt  
🔥 Severity: Critical  
🎯 SOC Action: Patch systems and investigate logs  

---

### 🔐 5. Credential Exposure (FTP)
- Plaintext credentials detected

🧠 Assessment: Insecure protocol usage  
🔥 Severity: High  
🎯 SOC Action: Enforce encrypted protocols  

---

## 🛡️ SOC Perspective
- Correlate alerts with SIEM logs (Splunk)
- Identify affected systems
- Contain suspicious activity
- Apply mitigation strategies

---

## 🧠 Skills Demonstrated
- Wireshark
- Network Traffic Analysis
- Threat Detection
- SOC Investigation

---

## 📸 Screenshots

See uploaded images below for full investigation evidence.

---

## 📌 Conclusion
This project demonstrates practical SOC investigation skills by identifying and analyzing multiple network-based threats.

---

## 👨‍💻 Author
Cybersecurity Student | Aspiring SOC Analyst | Security+ Certified
