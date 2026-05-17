# CodeAlpha - Basic Network Sniffer

## Project Overview

This project is developed as part of the CodeAlpha Cyber Security Internship.

The Basic Network Sniffer is a Python-based tool that captures and analyzes live network packets in real time using the Scapy library. The program helps understand how data travels through a network and displays important packet information such as source IP, destination IP, protocol type, and payload details.

---

## Features

* Live packet capturing
* Detects TCP, UDP, and ICMP protocols
* Displays source and destination IP addresses
* Shows incoming and outgoing traffic direction
* Displays packet payload information
* Real-time traffic monitoring

---

## Technologies Used

* Python 3
* Scapy Library
* Kali Linux / Linux Terminal

---

## Requirements

Install Scapy before running the program:

```bash
pip install scapy
```

---

## How to Run

Run the program with root privileges:

```bash
sudo python3 sniffer.py
```

---

## Sample Output

```text
----------------------------------------
Time            : 14:43:09
Direction       : Incoming
Source IP       : 185.199.108.133
Destination IP  : 192.168.1.66
Protocol        : TCP
Payload         : Not visible (possibly encrypted)
----------------------------------------
```

---

## Project Objective

The objective of this project is to:

* Capture live network traffic
* Understand packet structure
* Analyze network protocols
* Learn basics of network monitoring and packet inspection

---

## Screenshots

### TCP Packet Detection

(Add screenshot here)

### UDP Packet Detection

(Add screenshot here)

### ICMP Packet Detection

(Add screenshot here)

---

## Learning Outcomes

Through this project, I learned:

* Basics of packet sniffing
* Network traffic analysis
* Protocol identification
* Real-time packet monitoring using Python

---

## Internship Information

This project is submitted for:
CodeAlpha Cyber Security Internship – TASK 1: Basic Network Sniffer

---

## Author

Md Mohtasim
