# Cybersecurity Internship Task 1 Report

**Date:** July 2, 2025

**Intern:** Nehaa J

---

## 🔍 Task Objectives

* Scan the local network for open ports.
* Analyze network traffic using Wireshark.
* Understand basic network reconnaissance techniques.
* Document findings and upload them to GitHub.

---

## ✅ Task 1: Scan Your Local Network for Open Ports

### 🛠️ Tools Used

* **Nmap** – Network scanning and host discovery.
* **Wireshark** – Network packet analyzer.
* **ipconfig / ifconfig** – Network configuration inspection.
* **Tracert / Traceroute** – Route analysis.

---

## 📡 Network Setup

| Interface | IP Address    | MAC Address       |
| --------- | ------------- | ----------------- |
| Wi-Fi     | 192.168.1.100 | 8C-04-BA-27-A5-BD |
| Loopback  | 127.0.0.1     | N/A               |

---

## 🔎 Nmap Command Used

```bash
nmap -sS 192.168.1.0/24
```

### Nmap Scan Results

#### Host: 192.168.1.1 (Router)

**Open Ports:**

* 80/tcp – HTTP
* 443/tcp – HTTPS
* 53/tcp – DNS

#### Host: 192.168.1.100 (Local System)

* Most scanned ports were closed.
* No unnecessary services were exposed.

---

## 🧪 Wireshark Traffic Analysis

Captured live traffic on the active Wi-Fi interface.

### Observations

* TCP SYN packets observed.
* DNS request and response traffic observed.
* Normal communication between the device and router.
* TCP three-way handshake successfully captured.

### Findings

**Source:** 192.168.1.1
**Destination:** 192.168.1.100

The captured traffic indicated normal network communication and no suspicious activity was detected during the analysis period.

---

## 📸 Screenshot Evidence

The following screenshots are included in the repository:

✅ Network configuration using ipconfig

✅ Nmap scan results

✅ Wireshark packet capture

✅ Ping command output

✅ Traceroute command output

All screenshots are stored in the **/screenshots/** directory.

---

## 🎯 Learning Outcomes

Through this task, I learned:

* Basics of network reconnaissance.
* Identifying active hosts and open ports.
* Using Nmap for network scanning.
* Analyzing packets using Wireshark.
* Understanding TCP/IP communication.
* Documenting cybersecurity findings professionally.

---

## 📌 Conclusion

This task provided practical exposure to cybersecurity fundamentals. Nmap was used to identify active devices and services within the network, while Wireshark enabled packet-level traffic analysis. The exercise strengthened my understanding of network scanning, traffic monitoring, and cybersecurity assessment techniques.

---

## 📂 GitHub Repository Structure

Cybersecurity_Task_01_Nehaa_J

├── README.md

├── Cybersecurity_Task_01_Report.docx

├── findings.txt

└── screenshots/

    ├── ipconfig.png

    ├── nmap_scan.png

    ├── wireshark_capture.png

    ├── ping.png

    └── traceroute.png
