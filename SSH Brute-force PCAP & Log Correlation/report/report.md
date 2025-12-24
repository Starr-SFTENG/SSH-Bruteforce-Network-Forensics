# SSH Brute-force Attack Report

## Summary
Multiple failed SSH login attempts were made against the user `ubuntu` from IP 192.168.56.102, indicating a brute-force attempt. The attack was captured in both auth logs and PCAP data.

## Findings
- Unauthorized access attempts detected on `2025-12-23`.
- Attacker used multiple ports to attempt connections.
- Admin user `logside` performed tcpdump to capture the attack traffic.
- Correlation between log timestamps and packet capture confirms attack patterns.

## Recommendations
1. Implement rate limiting and fail2ban for SSH login attempts.
2. Use key-based authentication and disable password login.
3. Monitor logs and PCAPs regularly for unusual patterns.
