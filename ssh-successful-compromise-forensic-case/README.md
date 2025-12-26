# SSH Successful Compromise – Digital Forensics Case

This repository documents a forensic investigation into a confirmed SSH compromise
in a controlled VirtualBox lab environment.

## Scenario
An attacker successfully authenticated to an Ubuntu Server via SSH using valid
credentials. Network traffic and system logs were captured and analyzed to confirm
the compromise, correlate events, and reconstruct attacker activity.

## Lab Environment
- Attacker: Kali Linux
- Victim: Ubuntu Server
- Forensics: Windows 10
- Network: Host-only VirtualBox network

## Evidence
- auth.log (Linux authentication logs)
- ssh_successful_compromise.pcap (SSH network capture)

## Findings
- Unauthorized SSH login using valid credentials
- Interactive encrypted SSH session established
- Attempted privilege escalation
- Confirmed attacker-controlled session lifecycle

## Skills Demonstrated
- Log analysis
- PCAP analysis
- Timeline reconstruction
- Evidence correlation
- Incident reporting
