# Log Analysis

- **New User Creation:** `logside` created on 2025-12-21 (UID 1000)
- **Failed Login Attempts:**
  - Invalid user `ubuntu` attempted multiple logins on 2025-12-23 from 192.168.56.102
  - `pam_unix` authentication failures observed
- **Successful Capture:**
  - User `logside` ran `tcpdump` to capture attack traffic: `/usr/bin/tcpdump -i any -w attack_capture.pcap`
