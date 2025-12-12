# 🛡️ DFIR Tools Collection
A curated collection of **Digital Forensics & Incident Response (DFIR)** tools used for forensic investigation, malware analysis, incident response, memory forensics, disk analysis, and triage.

This toolkit includes tools from my DFIR environment + recommended industry-standard DFIR tools.

---

## 📌 Table of Contents
- [Overview](#overview)
- [Disk & File System Forensics](#disk--file-system-forensics)
- [Memory Forensics](#memory-forensics)
- [Malware Analysis](#malware-analysis)
- [Network Forensics](#network-forensics)
- [Log & Registry Analysis](#log--registry-analysis)
- [Browser & Email Forensics](#browser--email-forensics)
- [Triage & Incident Response](#triage--incident-response)
- [Data Recovery](#data-recovery)
- [Hex Editors & Binary Tools](#hex-editors--binary-tools)
- [Additional Recommended DFIR Tools](#additional-recommended-dfir-tools)
- [Conclusion](#conclusion)

---

## Overview
This toolkit is designed for:

- Digital forensic investigations  
- Malware and incident response  
- Live system triage  
- File, memory, registry, and network analysis  
- DFIR learning and CTF challenges  

---

## Disk & File System Forensics
### **🔹 Sleuth Kit**
Open-source forensic suite used to analyze partitions, recovered files, timestamps, and disk structures.

### **🔹 Disk Analysis**
Category containing tools for examining disk images (E01, RAW, VHD), partitions, file carving, etc.

### **🔹 Autopsy** *(Recommended)*
GUI forensic platform for analyzing digital media, recovering deleted files, and generating reports.

### **🔹 FTK Imager** *(Recommended)*
Used for creating forensic images and previewing disk contents without altering evidence.

---

## Memory Forensics
### **🔹 Memory Analysis**
May include Volatility, Volatility3, or Rekall for analyzing memory dumps.

### **🔹 Volatility / Volatility 3** *(Recommended)*
Industry-standard RAM forensics tool.  
Finds:
- Processes  
- Injected code  
- Network connections  
- DLLs  
- Malware in memory  

### **🔹 DumpIt / WinPMEM** *(Recommended)*
Tools used to acquire RAM images from live systems.

---

## Malware Analysis
### **🔹 Malware Analysis Folder**
General tools for analyzing malware behavior.

### **🔹 PEStudio**
Static analysis of executables to reveal suspicious indicators.

### **🔹 CAPA (Mandiant)** *(Recommended)*
Automatically identifies malware capabilities.

### **🔹 x64dbg / OllyDbg** *(Recommended)*
Debuggers for reverse engineering malware.

### **🔹 Ghidra** *(Recommended)*
NSA’s reverse engineering suite for binary analysis.

### **🔹 CyberChef** *(Recommended)*
Multi-purpose tool for decoding, deobfuscation, encryption, and data transformations.

---

## Network Forensics
### **🔹 Network Analysis**
Category for traffic analysis tools.

### **🔹 Wireshark** *(Recommended)*
Most widely used tool for investigating PCAP files.

### **🔹 Tshark**
Command-line packet analyzer.  

### **🔹 Zeek** *(Recommended)*
Generates metadata logs from network traffic (very useful for IR and timeline analysis).

### **🔹 Nmap**
Port and service scanning, OS fingerprinting, and vulnerability discovery.

---

## Log & Registry Analysis
### **🔹 LogFileParser**
Parses log files like Windows event logs, firewall logs, proxy logs, etc.

### **🔹 Registry Analysis**
Registry parsing tools such as:
- RegRipper  
- Registry Explorer  

### **🔹 Sysinternals Suite**
Includes:
- **Autoruns** – persistence detection  
- **Process Explorer** – process investigation  
- **Procmon** – event tracing  
- **TCPView** – network connection monitoring  

---

## Browser & Email Forensics
### **🔹 Browser Analysis**
Tools for viewing:
- History  
- Cookies  
- Cache  
- Autofill  
- Download records  

### **🔹 Email Analysis**
Supports PST, OST, MBOX, EML formats for email forensic investigations.

### **🔹 ExifTool**
Extracts metadata (EXIF, GPS, timestamps) from:
- Images  
- PDFs  
- Videos  
- Documents  

---

## Triage & Incident Response
### **🔹 EZ Tools (Eric Zimmerman Tools)**
Popular set of Windows forensic tools:
- KAPE  
- Registry Explorer  
- JumpList Explorer  
- ShellBags Explorer  
- USB Detective  

### **🔹 Aurora**
Rapid incident response triage tool.

### **🔹 Data Triaging**
Tools that quickly scan systems for malicious files, processes, and persistence mechanisms.

### **🔹 PersistenceSniper**
Detects hidden or abnormal persistence across:
- Run keys  
- Services  
- Scheduled tasks  
- WMI  

---

## Data Recovery
### **🔹 Recovery Data**
Tools for restoring deleted partitions, lost files, and corrupt storage devices.

### **🔹 PhotoRec / TestDisk** *(Recommended)*
Most widely used open-source recovery utilities.

---

## Hex Editors & Binary Tools
### **🔹 HxD**
Hex editor used for:
- Disk sector analysis  
- Binary inspection  
- File carving  
- Manipulating raw bytes  

---

## Additional Recommended DFIR Tools
### **Mobile Forensics**
- Cellebrite UFED  
- Magnet AXIOM Mobile  

### **Timeline Analysis**
- log2timeline (Plaso)  
- Timesketch  

### **Linux DFIR**
- OSQuery  
- Auditd  
- chkrootkit  

### **Cloud Forensics**
- AWS IR tools  
- Azure Sentinel playbooks  

---

## Conclusion
This DFIR toolkit provides a wide coverage of tools for:

✔ Disk forensics  
✔ Memory forensics  
✔ Network investigation  
✔ Malware analysis  
✔ Incident response  
✔ Registry & log analysis  
✔ USB & browser forensics  
✔ Data recovery  

It is suitable for both professional IR work and DFIR learning.

