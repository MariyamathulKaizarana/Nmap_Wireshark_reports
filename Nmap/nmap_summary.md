# Nmap Scan Summary

This file provides a quick overview of the Nmap scans performed in this repository.

| Scan File / Command        | Target IP       | Observations                                                                |
|----------------------------|-----------------|-----------------------------------------------------------------------------|
| nmap_scan1.png             | 192.168.56.1    | Open ports detected: 135 (msrpc), 139 (netbios-ssn), 445 (microsoft-ds),    | 
|                            |                 |    3306 (mysql). 996 other TCP ports are filtered.                          |
| nmap_notes.txt             | Local Network   | Notes on scan parameters, scan types used (port-specific and overall scan), |
|                            |                 |      and key observations.                                                  |

## Notes

- **Open** → Port is accepting connections.  
- **Filtered** → Port is blocked by firewall or filter; Nmap cannot determine status.  
- Scan performed for educational purposes only on authorized networks. 