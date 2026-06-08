# 🌐 Networking Task 01 — Understanding Your Network Environment
 
**Author:** Denny Xalxo
**Task:** Networking Task 01
**Domain:** Computer Networking — Internship Assignment
 
---
 
## 📋 Overview
 
This task explores the fundamentals of computer networking by examining a real device's network configuration, understanding core networking concepts, creating a basic network topology diagram, and performing connectivity tests using command-line tools.
 
---
 
## File Structure
 
```
Networking_Task_01_Denny_Xalxo.docx   # Main task submission document
README.md                              # This file
```
 
---
 
##  Task Breakdown
 
### Part A — Network Information
Identification and documentation of key network parameters of a local device:
 
| Parameter | Description |
|-----------|-------------|
| Hostname | Device name on the network |
| IPv4 Address | Logical address assigned to the device |
| MAC Address | Hardware identifier of the network adapter |
| Default Gateway | Router IP for external network communication |
| DNS Server | Server that resolves domain names to IP addresses |
 
---
 
### Part B — Basic Networking Concepts
 
Conceptual understanding of core networking terminology:
 
- **IP Address** — A unique numerical label assigned to each device on a network for identification and communication.
- **MAC Address** — A hardware-level identifier permanently assigned to a network interface card (NIC) by its manufacturer.
- **Default Gateway** — The router that acts as the access point for sending data from the local network to external networks (e.g., the Internet).
- **DNS (Domain Name System)** — A system that translates human-readable domain names (e.g., `google.com`) into IP addresses.
**Public IP vs. Private IP:**
 
| Feature | Public IP | Private IP |
|---------|-----------|------------|
| Visibility | Visible on the Internet | Used inside local network only |
| Assignment | Assigned by ISP | Assigned by router (DHCP) |
| Uniqueness | Globally unique | Can be reused across networks |
 
---
 
### Part C — Basic Network Diagram
 
A simple diagram illustrating how a device connects to the Internet:
 
```
        ☁️  Internet
             ↓
       📡  ISP Network
             ↓
       📶  WiFi Router
    (Default Gateway: 192.168.1.1)
             ↓
        💻  Laptop
      (IPv4: 192.168.1.100)
```
 
---
 
### Part D — Network Connectivity Test
 
Command-line tools used for network diagnostics on Windows:
 
```bash
ipconfig          # View network configuration details
ping google.com   # Test connectivity to a remote server
tracert google.com  # Trace the route packets take to a destination
```
 
**Results Summary:**
 
| Test | Result |
|------|--------|
| Ping to google.com | ✅ Successful — replies received |
| Number of hops (tracert) | 4 hops (Router → ISP → ISP Gateway → Google) |
| Purpose of Traceroute | Displays the path taken by packets and helps diagnose network issues |
 
---
 
## Tools & Commands Used
 
- `ipconfig` — Windows command to display network configuration
- `ping` — Tests network reachability and measures round-trip time
- `tracert` — Traces the route taken by packets across an IP network
---
 
##  Key Concepts Covered
 
- Network addressing (IPv4, MAC)
- Public vs. Private IP addressing
- DNS resolution
- Default gateway and routing
- Network topology (basic)
- Packet transmission and hop analysis
---
 
##  About
 
This is an internship assignment focused on building foundational knowledge in computer networking. The task involves both theoretical understanding and hands-on command-line practice.
 

