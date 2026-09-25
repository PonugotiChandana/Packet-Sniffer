# Packet Sniffer Project

## Overview

Packet Sniffer is a Java-based network monitoring and packet analysis application that captures, inspects, and analyzes network traffic in real time. The project provides detailed information about packets flowing through a network interface, helping users understand network communication, troubleshoot issues, and study networking protocols.

The application supports analysis of multiple network protocols and presents packet-level information through a graphical interface.

---

## Features

### Packet Capture
- Real-time packet capturing
- Network interface selection
- Start and stop packet capture
- Save captured packets

### Protocol Analysis
- Ethernet Packet Analysis
- ARP Packet Analysis
- IPv4 Analysis
- IPv6 Analysis
- TCP Analysis
- UDP Analysis
- ICMP Analysis

### Application Layer Protocols
- HTTP Traffic Analysis
- FTP Traffic Analysis
- SMTP Traffic Analysis
- POP3 Traffic Analysis
- SSH Traffic Analysis
- Telnet Traffic Analysis

### Statistics Monitoring
- Network Protocol Statistics
- Application Protocol Statistics
- Memory Usage Monitoring
- Traffic Analysis Reports

---

## Technology Stack

### Programming Language
- Java

### Networking Library
- Jpcap Library

### GUI
- Java Swing

### Development Environment
- Eclipse IDE / NetBeans

---

## Project Structure

```
Packet-Sniffer-Project/
│
├── analyzer/
│   ├── ARPAnalyzer.java
│   ├── EthernetAnalyzer.java
│   ├── ICMPAnalyzer.java
│   ├── IPv4Analyzer.java
│   ├── IPv6Analyzer.java
│   ├── TCPAnalyzer.java
│   ├── UDPAnalyzer.java
│   ├── HTTPAnalyzer.java
│   ├── FTPAnalyzer.java
│   ├── SMTPAnalyzer.java
│   ├── POP3Analyzer.java
│   ├── SSHAnalyzer.java
│   └── TelnetAnalyzer.java
│
├── stat/
│   ├── ApplicationProtocolStat.java
│   ├── NetworkProtocolStat.java
│   └── FreeMemStat.java
│
├── image/
│
└── Main Application Files
```

---

## System Workflow

1. Select Network Interface Card (NIC)
2. Start Packet Capture
3. Capture Incoming and Outgoing Packets
4. Identify Protocol Type
5. Analyze Packet Headers and Data
6. Display Packet Details
7. Generate Traffic Statistics
8. Save Captured Information

---

## Installation

### Prerequisites

- Java JDK 8 or Higher
- Eclipse IDE / NetBeans
- Jpcap Library
- WinPcap / Npcap (Windows)

### Steps

1. Install Java JDK.
2. Install WinPcap or Npcap.
3. Download and configure Jpcap library.
4. Import the project into Eclipse or NetBeans.
5. Add Jpcap JAR files to project libraries.
6. Build the project.
7. Run the application.

---

## How to Use

1. Launch the application.
2. Select the desired network adapter.
3. Click **Start Capture**.
4. Monitor incoming and outgoing packets.
5. View protocol-specific analysis.
6. Stop capturing when required.
7. Save packet logs if needed.

---

## Applications

- Network Monitoring
- Cybersecurity Learning
- Protocol Analysis
- Network Troubleshooting
- Traffic Inspection
- Academic Research
- Ethical Hacking Labs

---

## Future Enhancements

- Deep Packet Inspection (DPI)
- Packet Filtering Rules
- Intrusion Detection Features
- Real-Time Traffic Graphs
- Export Reports to PDF
- Machine Learning Based Threat Detection
- Cloud Monitoring Support

---

## Learning Outcomes

- Computer Networks
- TCP/IP Protocol Suite
- Packet Analysis
- Network Security Fundamentals
- Java Network Programming
- Traffic Monitoring Techniques

---

## Author

**Risha Reddy Minukuri**  
B.Tech Computer Science Engineering  
Anurag University

---

## License

This project is intended for educational and research purposes only.
