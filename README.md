# SOC Investigation - Nmap Scan Detection

Used Kali Linux to perform an Nmap scan and Wireshark to capture traffic.

Applied filter:
tcp.flags.syn == 1 && tcp.flags.ack == 0

Detected SYN scan behavior (multiple ports from single source).

Mapped to MITRE ATT&CK: T1046 (Network Service Scanning)
Full report is attached.
