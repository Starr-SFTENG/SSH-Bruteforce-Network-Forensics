# PCAP Analysis

- **Attacker IP:** 192.168.56.102
- **Victim IP:** 192.168.56.103
- **Protocol:** SSH
- **Key Observations:**
  - Repeated encrypted packet exchanges.
  - Connection attempts to multiple ports (56954, 56970, 56972, etc.).
  - SSHv2 protocol used by client: libssh_0.11.3
  - Server responded with multiple ACKs and FINs, rejecting invalid users.

**Conclusion:** The PCAP confirms multiple unauthorized SSH connection attempts consistent with a brute-force attack.
