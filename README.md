# International School Network Infrastructure Design

## 📌 Project Overview
This project presents the design and implementation of a secure, scalable, and redundant enterprise network for an **International School** with two campuses: **Cairo** and **Alexandria**.  
The network was built to ensure high availability, controlled access, secure Internet connectivity, and efficient network management.

---

## 🏫 Network Architecture
- Multi-site campus network (Cairo & Alexandria)
- Core–Distribution–Access hierarchical design
- Wired and wireless access for end users
- Centralized control and policy enforcement

---

## 🔐 Network Policies & Security
- Campus devices (Cairo & Alexandria) can access all internal resources **except database servers**
- Control and policy networks have **full access** across the infrastructure
- **NAT policies** allow campus users Internet access for **HTTP/HTTPS browsing and ICMP (ping) only**
- Secure **remote access** enabled for Network and Security teams

---

## ⚙️ Implemented Technologies
- **Routing & Switching**
  - VLANs and inter-VLAN routing
  - Layer 3 Switching
  - Static routing
- **Redundancy & High Availability**
  - HSRP for core network gateway redundancy
  - EtherChannel (LAG) between core switches
- **Layer 2 Stability**
  - PVST on all uplink switches
  - PortFast enabled on access ports
- **Network Services**
  - DHCP for all end devices
  - Wireless connectivity via Access Points
- **Security & Traffic Control**
  - NAT with protocol-based access control
  - Access control policies for sensitive resources

---

## 📡 Wireless Network
- All laptops connect via Wireless Access Points
- Integrated seamlessly with the wired campus network

---

## 🛠 Tools Used
- Cisco Packet Tracer
- Wireshark

---

## 🎯 Key Outcomes
- High availability and redundancy at the core layer
- Secure and controlled access to critical resources
- Reliable wired and wireless connectivity for all users
- Enterprise-grade network design suitable for large institutions

---

## 📎 Notes
This project was designed and configured as part of hands-on networking practice, focusing on **enterprise networking, security policies, and high availability concepts**.

