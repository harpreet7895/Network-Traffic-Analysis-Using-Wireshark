# Network Traffic Analysis Using Wireshark

## 📌 Project Overview

This project demonstrates how to capture, monitor, and analyze network traffic using **Wireshark**, one of the most widely used network protocol analyzers. The objective is to understand how data travels across a network, inspect different protocols, and analyze real-time communication between devices.


## 🎯 Objectives

- Capture live network traffic.
- Analyze common network protocols.
- Understand packet structure.
- Monitor DNS, TCP, TLS, and ICMP traffic.


## 🛠️ Technologies Used

- Kali Linux
- Wireshark
- Firefox Browser
- VirtualBox
- TCP/IP Networking


## 📚 Protocols Analyzed

- DNS
- TCP
- TLS (HTTPS)
- ICMP
- IPv4
- Ethernet II


## 🚀 Implementation Steps

1. Install Wireshark.
2. Launch Wireshark.
3. Select the **eth0** network interface.
4. Start packet capture.
5. Generate traffic by visiting websites.
6. Apply display filters:
   - dns
   - tcp
   - tls
   - icmp
7. Analyze packet details.
8. View Protocol Hierarchy.
9. View Conversations.
10. View Endpoints.
11. Save the capture as a `.pcapng` file.


## ⚙️ Installation

### Step 1: Update System

```bash
sudo apt update
sudo apt upgrade -y
```

### Step 2: Install Wireshark

```bash
sudo apt install wireshark -y
```

### Step 3: Add Current User to Wireshark Group

```bash
sudo usermod -aG wireshark $USER
```

### Step 4: Restart the System

```bash
sudo reboot
```

### Step 5: Verify Installation

```bash
wireshark --version
```

### Step 6: Launch Wireshark

```bash
wireshark
```

## 💻 Display Filters Used

```text
dns
tcp
tls
icmp
http
udp
```


## 📊 Results

- Successfully captured live network traffic.
- Identified DNS requests and responses.
- Observed TCP three-way handshake.
- Inspected encrypted TLS communication.
- Monitored ICMP echo requests and replies.
- Generated protocol statistics using Wireshark.


## 🎓 Learning Outcomes

- Learned packet capturing techniques.
- Understood network communication.
- Analyzed multiple network protocols.
- Used Wireshark filters effectively.
- Improved practical cybersecurity skills.


##  Author

Harpreet Kaur

BCA (Cyber Security & Forensics)

CT University
