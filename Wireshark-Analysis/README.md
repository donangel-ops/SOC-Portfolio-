# Wireshark Analysis - rk_eth0P5YOW3.pcapng

## Objective
Analyze captured traffic for suspicious activity.

## Tools Used
Wireshark on Kali Linux

## Findings
- Protocol: TCP, DNS, HTTP
- Investigation steps: Filtered by ip.addr, followed TCP stream
- IoCs Found: Malware download attempt detected

## Evidence - My Screenshots
![Screenshot 1](Screenshot from 2026-10-14 18-00-49.png)
![Wireshark DNS](wireshark-dns.png)
![Wireshark HTTP](wireshark-http.png)

## MITRE ATT&CK
- T1040 - Network Sniffing
- T1071 - Application Layer Protocol
