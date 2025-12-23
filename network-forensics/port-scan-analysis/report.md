# Network Port Scan Forensic Report

## 1. Case Information
**Case Name:** Network Port Scan Investigation  
**Analyst:** Denzel T Mchawaya  
**Date:** 23/12/2025
**Environment:** Controlled Cyber Security Lab  

---

## 2. Objective
The purpose of this investigation was to analyze captured network traffic to determine whether malicious reconnaissance activity occurred and to document the findings in a forensically sound manner.

---

## 3. Evidence Description
- **Evidence Type:** Network traffic log
- **File Name:** portscan.csv
- **Format:** CSV
- **Source:** Packet capture converted to structured log format

---

## 4. Methodology
The analysis followed standard digital forensic procedures:
1. Evidence identification
2. Evidence examination
3. Traffic pattern analysis
4. Interpretation and conclusion

---

## 5. Analysis and Findings
Analysis of the traffic revealed:
- Sequential probing of multiple destination ports
- High frequency of connection attempts
- Single source IP targeting one host

These indicators are consistent with a **TCP SYN port scanning attack**, commonly used for service enumeration.

---

## 6. Interpretation
The observed behavior strongly suggests reconnaissance activity rather than normal user behavior. Port scanning is often performed to identify vulnerable services prior to exploitation.

---

## 7. Conclusion
The investigation confirms that the captured traffic represents a deliberate network port scanning attempt. No evidence of successful exploitation was observed during this analysis.

---

## 8. Recommendations
- Implement intrusion detection systems (IDS)
- Configure firewall rules to limit unnecessary open ports
- Monitor logs for repeated reconnaissance attempts

---

## 9. Chain of Custody
The evidence was handled within a controlled lab environment. No modifications were made to the original data during analysis.

---

## 10. Disclaimer
This analysis was conducted strictly for academic and training purposes.
