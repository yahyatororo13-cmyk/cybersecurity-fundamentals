# Networking Fundamentals

This document contains my learning notes about computer networking.
I am currently learning the basics required for cybersecurity and IT security roles.

---

## What is a Network?
A network is a group of devices (computers, servers, routers) that are connected together to share data and resources.

Examples:
- Home network
- Company network
- Internet

---

## Types of Networks
- LAN (Local Area Network)
- WAN (Wide Area Network)
- WLAN (Wireless LAN)

LAN is used inside homes and companies.
WAN is used to connect networks over long distances (example: the Internet).

---

## OSI Model
The OSI model has 7 layers:

1. Physical – cables, signals
2. Data Link – MAC addresses, switches
3. Network – IP addresses, routing
4. Transport – TCP / UDP
5. Session
6. Presentation
7. Application – HTTP, FTP, DNS

The OSI model helps understand how data moves inside a network.

---

## IP Address
An IP address is a unique number assigned to a device in a network.

Examples:
- IPv4: 192.168.1.1
- IPv6: 2001:db8::1

There are:
- Private IP addresses (used inside networks)
- Public IP addresses (used on the Internet)

---

## TCP vs UDP
TCP:
- Connection-oriented
- Reliable
- Slower
- Used for HTTP, HTTPS, FTP

UDP:
- Connectionless
- Faster
- Less reliable
- Used for DNS, streaming, gaming

---

## Ports
Ports are used to identify services on a device.

Examples:
- Port 80 → HTTP
- Port 443 → HTTPS
- Port 22 → SSH
- Port 53 → DNS

---

## What I Learned
- Basic network concepts
- How data travels between devices
- Difference between TCP and UDP
- Importance of ports in cybersecurity

---

## Next Steps
- Learn subnetting
- Practice with tools like ping and nmap
- Study network security basics
🧮 Subnetting (Basic Level)

Subnetting is the process of dividing a network into smaller networks (subnets).

Why subnetting is important:

Better network organization

Improved security

Reduced network congestion

Example:

Network: 192.168.1.0/24

Subnet mask: 255.255.255.0

Available IPs: 254 usable addresses

I am currently learning subnetting step by step.

🧭 Routing

Routing is the process of choosing the best path for data to travel between networks.

Routers:

Connect different networks

Use routing tables

Decide where to send packets

Example:

Home router connects LAN to the Internet

🔄 Switching

Switches are used inside LAN networks.

Functions:

Use MAC addresses

Send data only to the correct device

Reduce collisions in the network

Difference between Hub and Switch:

Hub sends data to all devices

Switch sends data only to the target device

🔐 Network Security Basics

Basic network security concepts:

Firewall: controls incoming and outgoing traffic

IDS (Intrusion Detection System): detects suspicious activity

IPS (Intrusion Prevention System): blocks malicious traffic

Security is essential to protect networks from attacks.

🛠️ Basic Networking Tools

Some basic tools I learned:

ping – checks connectivity

ipconfig / ifconfig – shows network configuration

tracert / traceroute – shows packet path

netstat – shows network connections

These tools are important for troubleshooting and security analysis.

🌍 DNS (Domain Name System)

DNS translates domain names into IP addresses.

Example:

google.com → 142.250.x.x

Without DNS, users would need to remember IP addresses.

🧠 What I Understand So Far

How devices communicate in a network

Role of routers and switches

Importance of network security

How DNS and IP addressing work together

🚀 Next Networking Goals

Learn subnetting deeply

Understand NAT

Practice network scanning in legal labs

Learn about VPN basics
