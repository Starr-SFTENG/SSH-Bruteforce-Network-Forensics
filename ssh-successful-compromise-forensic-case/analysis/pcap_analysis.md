# PCAP Analysis – SSH Session

## Network Overview

- Attacker IP: 192.168.56.102
- Victim IP: 192.168.56.103
- Protocol: SSHv2 (TCP/22)

## Key Observations

- TCP three-way handshake completed successfully
- SSH protocol negotiation observed
- Diffie-Hellman key exchange completed
- Sustained encrypted traffic indicates interactive session
- Clean session termination by client

## Session Characteristics

- Single long-lived SSH TCP stream
- Continuous encrypted packets
- No evidence of dropped or reset connections

## Conclusion

The PCAP confirms a stable SSH session corresponding to the compromised login.
