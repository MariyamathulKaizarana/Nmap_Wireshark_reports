# Network Analysis: Nmap & Wireshark

This repository contains my hands-on practice with **Nmap** and **Wireshark** for network scanning and traffic analysis. It documents scans, packet captures, and key observations for educational purposes.

## Repository Structure

network-analysis/
│
├─ Nmap/
│ ├─ nmap_scan1.png
│ ├─ nmap_notes.txt
│ └─ summary.md
│
├─ Wireshark/
│ ├─ capture1.png
│ ├─ capture2.png
│ ├─ capture3.png
│ ├─ wireshark_notes.txt
│ └─ summary.md
│
└─ README.md


- **Nmap/** – Contains screenshots and notes from network scanning exercises. See `summary.md` for a detailed overview of all scans.  
- **Wireshark/** – Contains packet captures (`.pcap`) and screenshots of filtered traffic. See `summary.md` for a detailed overview of captures.  

---

## Purpose

- Document practical experience with Nmap and Wireshark.  
- Learn and analyze network behavior, protocols, and open ports.  
- Build a reference for networking concepts and traffic analysis.  

---

## How to Use

1. Open the **Nmap/** folder to view scan screenshots and notes.  
   - Refer to `summary.md` for a quick overview of open ports and filtered ports.  
2. Open the **Wireshark/** folder to view packet captures and filtered screenshots.  
   - Use Wireshark software to open `.pcap` files for detailed analysis.  
   - `summary.md` provides an overview of each capture and applied filters.  

---

## Notes

- Nmap scan types included:
  - Port-specific scans (e.g., SSH `-p 22`, HTTP `-p 80`)  
  - Full TCP port scan (overall scan)  
- Wireshark captures include:
  - Overall capture (all traffic)  
  - TCP-filtered capture  
  - UDP-filtered capture  
- **Open** → Port is accepting connections.  
- **Filtered** → Port is blocked by firewall or filter; status cannot be determined.  
- These scans and captures were performed **for educational purposes only on authorized networks**.  

---

## References

- [Nmap Official Documentation](https://nmap.org/book/man.html)  
- [Wireshark Official Documentation](https://www.wireshark.org/docs/)  


