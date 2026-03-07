# cybersecurity-portfolio
A collection of cybersecurity labs, projects, and reports by Thapelo Nyapele.
# Nmap Network Scan

## Objective
To discover open ports and services on a target host using Nmap.

## Tool Used
Nmap on Kali Linux

## Command Used
nmap -sV 192.168.56.101

## Findings
The scan revealed that all scanned TCP ports were filtered. 
This suggests that firewall rules or network filtering mechanisms 
are preventing responses from the host.

## Conclusion
The system appears to have strong firewall protections because 
no accessible services were discovered.
## Evidence

### Nmap Scan Result

![Nmap Scan](Nmap-scan-result.png)

### Additional Scan Output

![Nmap Scan 2](Nmap-scan-result-01.png)
