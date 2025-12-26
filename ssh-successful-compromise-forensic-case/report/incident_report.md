# Incident Report – SSH Successful Compromise

## Executive Summary
A forensic investigation confirmed an unauthorized SSH login to an Ubuntu Server
using valid user credentials. The attacker established an interactive encrypted
session and attempted post-compromise actions.

## Incident Details
- Incident Type: Unauthorized Access (Valid Accounts)
- MITRE ATT&CK: T1078
- Severity: High
- Affected System: Ubuntu Server

## Evidence Analyzed
- Linux authentication logs (auth.log)
- Network traffic capture (PCAP)

## Findings
- Successful SSH authentication from 192.168.56.102
- Interactive SSH session lasting ~9 minutes
- Failed privilege escalation attempts
- No evidence of persistence achieved

## Impact Assessment
- Confidentiality compromised
- Integrity at risk
- No availability impact observed

## Recommendations
- Enforce SSH key-based authentication
- Disable password authentication
- Restrict SSH access via firewall rules
- Implement intrusion detection and alerting
- Monitor authentication logs continuously
