🛡️ DFIR Tools Collection

A curated collection of Digital Forensics & Incident Response (DFIR) tools used for forensic investigation, malware analysis, incident response, memory forensics, disk analysis, and triage.

This repository includes tools from my DFIR environment (screenshot folders) + additional industry-recommended DFIR tools.

📌 Table of Contents

Overview

Disk & File System Forensics

Memory Forensics

Malware Analysis

Network Forensics

Log & Registry Analysis

Browser & Email Forensics

Triage & Incident Response

Data Recovery

Hex Editors & Binary Tools

Additional Recommended DFIR Tools

## 📘 Overview

This toolkit is designed for:

Digital forensic investigations

Malware and incident response

Live system triage

File, memory, registry, and network analysis

DFIR learning and CTF challenges

📂 Disk & File System Forensics
🔹 Sleuth Kit

Open-source forensic suite with tools to analyze partitions, file systems, deleted files, timestamps, and disk artifacts.

🔹 Disk Analysis

Category containing tools like FTK Imager, Autopsy modules, or raw disk inspection utilities.

🔹 Autopsy (Recommended Tool)

GUI-based digital forensic platform used for analyzing disk images, recovering deleted files, and processing evidence.

🔹 FTK Imager (Recommended Tool)

Used to create forensic images and preview disk contents without altering evidence.

🧠 Memory Forensics
🔹 Memory Analysis

Folder may include Volatility / Volatility3 / Rekall.

🔹 Volatility / Volatility 3 (Recommended)

Industry-standard framework for RAM forensics:

Processes & injected code

Network connections

DLLs

Malware in memory

Registry hives inside RAM

🔹 DumpIt / WinPMEM (Recommended)

Tools to acquire live RAM images.

🦠 Malware Analysis
🔹 Malware Analysis

General category for static/dynamic analysis tools.

🔹 PEStudio

Examines executables for suspicious features (imports, sections, behaviors).

🔹 x64dbg / OllyDbg (Recommended)

Debuggers for reverse engineering malware.

🔹 CAPA (by Mandiant) (Recommended)

Automatically detects malware capabilities such as persistence, credential theft, or injection.

🔹 Ghidra (Recommended)

NSA’s reverse engineering suite for analyzing binaries.

🔹 CyberChef (Recommended)

Swiss-army knife for decoding, deobfuscation, hashing, and data transformations.

🌐 Network Forensics
🔹 Network Analysis

Category including PCAP analyzers.

🔹 Wireshark (Recommended)

Most widely used tool for analyzing PCAP files, packet-level details, and detecting threats.

🔹 Zeek (Recommended)

Network monitoring system that generates logs useful in DFIR investigations.

🔹 Tshark

Command-line version of Wireshark.

🔹 Nmap

Port and service scanner used to identify open ports, OS versions, and possible vulnerabilities.

📜 Log & Registry Analysis
🔹 LogFileParser

Parses system logs (event logs, firewall logs, web logs) for suspicious events.

🔹 Registry Analysis

Tools like RegRipper or Registry Explorer for analyzing:

Recently used files

USB artifacts

Program execution history

User activity

🔹 Sysinternals Suite

A powerful collection for live forensics:

Autoruns (persistence detection)

Process Explorer (process inspection)

Procmon (system activity tracing)

TCPView (network activity)

🌐 Browser & Email Forensics
🔹 Browser Analysis

Tools for analyzing:

History

Cookies

Autofill

Downloads

Login data

🔹 Email Analysis

Tools for PST/OST, MBOX, EML file parsing.
Useful for phishing, fraud, and insider investigations.

🔹 EXIFTool

Extracts metadata from images, PDFs, documents, videos, etc. Used in OSINT and timeline building.

🚀 Triage & Incident Response
🔹 EZ Tools (Eric Zimmerman Tools)

Most popular DFIR tools for Windows artifacts:

KAPE (triage collection)

ShellBags Explorer

USB Detective

Registry Explorer

JumpList Explorer

RecentFileCache parser

🔹 Aurora

Quick triage tool to gather system information, persistence artifacts, and logs.

🔹 Data Triaging

Quick scanning utilities to identify malicious files, processes, and indicators.

🔹 PersistenceSniper

Detects persistence mechanisms on Windows systems (scheduled tasks, services, WMI, Run keys).

🔄 Data Recovery
🔹 Recovery Data

Tools for recovering:

Deleted files

Damaged partitions

Broken USB drives

Corrupted file systems

🔹 PhotoRec / TestDisk (Recommended)

Most widely used open-source recovery tools.

🔧 Hex Editors & Binary Tools
🔹 HxD

Hex editor for analyzing:

Raw disk sectors

File bytes

Memory segments
Used to identify fragments, signatures, file carving, or corruption.

⭐ Additional Recommended DFIR Tools
Mobile Forensics

Cellebrite UFED

Magnet AXIOM Mobile

Cloud Forensics

AWS IR tools

Azure Sentinel log analyzers

Timeline Tools

log2timeline / Plaso

Timesketch

Linux DFIR Tools

Auditd

OSQuery

chkrootkit

📌 Conclusion

This DFIR toolkit provides a well-rounded environment for:
✔ Disk forensics
✔ Memory analysis
✔ Malware reverse engineering
✔ Network investigation
✔ Log and registry analysis
✔ Quick triage
✔ Incident response
✔ Data recovery
