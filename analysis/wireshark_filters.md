# Wireshark Display Filters Used

- SSH Traffic:

tcp.port == 22


- TCP SYN Scan Detection:
tcp.flags.syn == 1 && tcp.flags.ack == 0


- SSH Sessions:


These filters were used to isolate suspicious traffic patterns during analysis.
