# 📡 Large Conference Management Network Simulation (Cisco Packet Tracer)

This project simulates a complete networking environment for a **Large Conference Management Company** using **Cisco Packet Tracer**. It includes server setups, VLANs, wireless access, ACLs, bandwidth limits, and proper IP subnetting — all designed for real-world organizational use cases.

## 🧠 Scenario Overview

- A fiber connection from ISP (192.168.10.1/28) delivers 300 Mbps bandwidth.
- Server Room manages all core services: **DHCP**, **DNS**, **Proxy**, **WebServer**, and **Firewall**.
- Three main halls (H1, H2, H3), multiple departments (IT, Finance, Office, Coordinating, Advertisement).
- Each department and hall has **1 PC for testing purposes**.
- VLANs are configured to isolate departments.
- Bandwidth is controlled using **QoS**:
  - Halls: Max 2 Mbps/user.
  - Halls overall: Limited to 50 Mbps.
  - Departments (except IT): Limited to 5 Mbps/user.

## 📁 Folder Structure

```bash
📦LargeConferenceNetworkSimulation
 ┣ 📜README.md
 ┣ 📄Network_Design_Report.docx
 ┣ 📁screenshots/
 ┃ ┣ 🖼️ topology.png
 ┃ ┣ 🖼️ vlan-config.png
 ┃ ┗ 🖼️ wireless-settings.png
 ┗ 📁packet_tracer_file/
   ┗ 📦LargeConferenceNetwork.pkt
