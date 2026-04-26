# 🌐 Cisco Networking Project 2025: Scalable SME Infrastructure

## 📋 Project Description
This project involves the design and simulation of a comprehensive, realistic, and scalable network infrastructure for a small to medium-sized enterprise (SME). The objective was to bridge the gap between theoretical concepts and a functional networking solution addressing connectivity, performance, and security requirements.

**Software Used:** Cisco Packet Tracer v8.2.2

---

## 🏗️ Network Architecture
The network is based on a hierarchical design (Core, Distribution, Access) to optimize traffic flow and simplify maintenance.

*   **Headquarters (HQ):** Includes a Data Center hosting critical services (DNS, DHCP, HTTP, FTP).
*   **Remote Branches:** Two branch offices securely connected to the headquarters' resources.
*   **Internet Access:** Dedicated Gateway via a simulated ISP router.

### Key Technical Features:
*   **Logical Segmentation:** Implementation of **VLANs** to isolate services (Admin, Servers, Users) and enhance security.
*   **IP Optimization:** Used **VLSM (Variable Length Subnet Masking)** for efficient IP address space allocation.
*   **Routing:** A mix of static and dynamic routing to ensure redundancy and inter-site reachability.
*   **Security:** Implementation of Access Control Lists (**ACLs**) to filter inter-VLAN and outbound Internet traffic.

---

## 📸 Visuals & Proof of Concept

### Logical Topology

*Global view of the Packet Tracer topology showing the HQ and the two branches.*  

<img width="1600" height="814" alt="image" src="https://github.com/user-attachments/assets/3363735e-7c5d-4136-b360-b24da2ebbd15" />



### Connectivity & Services Tests
*Verification of DNS resolution and successful ICMP (Ping) requests across all segments.*  

<img width="1052" height="977" alt="image" src="https://github.com/user-attachments/assets/ff2f1fb7-19c8-4dfa-bb74-9e598d84e45a" />   
<img width="1600" height="813" alt="image" src="https://github.com/user-attachments/assets/d0977fa7-acd2-40c6-a52a-a4a1df980f60" />   
<img width="944" height="900" alt="Capture d&#39;écran 2025-12-24 135008" src="https://github.com/user-attachments/assets/2aaecbad-f372-4c40-b377-6b3230d483e4" />
  
---
       
*Configuration of IP adresses.* 

<img width="1116" height="744" alt="image" src="https://github.com/user-attachments/assets/ead57fe6-3c19-4581-b966-c26657539d38" />
<img width="1038" height="464" alt="image" src="https://github.com/user-attachments/assets/a7428d75-9c42-4dbf-8a31-155090b0f9b2" />

---

## 🚀 Demonstrated Skills
*   **Planning:** Created a structured IP addressing plan.
*   **CLI Configuration:** Proficiency in the Cisco Command Line Interface (IOS).
*   **Network Services:** Configuration of DHCP servers, DNS, and default gateways.
*   **Troubleshooting:** Analysis of routing tables and network diagnostics.

---

## 📂 Repository Content
*   `projet cisco`: Source file `.pkt` (Cisco Packet Tracer).
*   `/docs`: Detailed PDF project documentation.
*   `/images`: Screenshots of the topology and connectivity tests.

---
*Project developed as part of an in-depth study of distributed systems and practical networking.*
