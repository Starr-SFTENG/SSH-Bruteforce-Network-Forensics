# Network Port Scan Forensic Analysis

##  Project Overview
This project documents a forensic investigation of a network port scanning activity detected within a controlled cyber security lab environment. The objective was to identify, analyze, and interpret suspicious network behavior using captured traffic data.

The investigation focuses on recognizing reconnaissance activity, a common precursor to cyber attacks.

---

##  Lab Environment
- **Attacker Machine:** Kali Linux
- **Target System:** Ubuntu Server
- **Network Type:** Host-Only Network
- **Data Source:** Network traffic log (CSV format)

---

##  Tools Used
- Nmap (attack simulation)
- Wireshark / tcpdump (traffic capture)
- CSV log analysis
- Markdown documentation

---

##  Key Findings
- Multiple connection attempts to sequential ports
- Repeated probes from a single source IP
- Behavior consistent with TCP SYN port scanning

---

##  Repository Structure

portscan-forensic-case/
├── README.md
├── report.md
├── data/
│ └── portscan.csv


---

##  Learning Outcomes
- Identification of reconnaissance activity
- Understanding attacker enumeration techniques
- Proper forensic documentation for SOC and DFIR roles

---

## Disclaimer
This project was conducted in an isolated lab environment for educational purposes only.
