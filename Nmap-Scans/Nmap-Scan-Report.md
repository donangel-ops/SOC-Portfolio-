# Nmap Recon Project

## Target
- Host: scanme.nmap.org
- IP: 45.33.32.156
- Date: Oct 14 2026

## Command
nmap -F scanme.nmap.org

## Results
- Host Status: UP
- Ports Scanned: 100
- Result: All ports FILTERED
- Latency: 0.00088s
- Scan Time: 2.14 sec

## Analysis
Filtered means firewall is dropping packets. This is good security - it hides whether ports are open or closed. Target has strong firewall rules.

## SOC Insight
Next steps for analyst:
1. Try SYN scan (-sS)
2. Check firewall logs
3. Correlate with threat intel

## MITRE ATT&CK
T1046 - Network Service Discovery

## Tools
Nmap 7.991 on Kali Linux
