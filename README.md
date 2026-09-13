# 🏢 Enterprise Multi-Floor Network Design – CCNA Final Project

A complete enterprise network design and configuration project built in Cisco Packet Tracer, developed as the capstone project for the CCNA-based Summer Training program at the **National Telecommunication Institute (NTI)**.

## 📋 Project Overview

The project scenario involved designing and configuring the network infrastructure for a **three-floor office building**, with each floor having its own router and switch, and each floor hosting multiple departments.

| Floor | Departments |
|-------|-------------|
| Floor 1 | Reception, Store, Logistics |
| Floor 2 | Finance, HR, Sales |
| Floor 3 | Administration, IT |

Each department includes **2 PCs and 1 printer**, with the goal of achieving full end-to-end connectivity across the entire building.

## 🗺️ Topology

- **3 switches**, each hosting a set of department VLANs
- **3 routers**, one per floor, running **OSPF** for inter-floor routing
- **8 VLANs** total across the switches
- **Router-on-a-Stick** used for inter-VLAN routing via subinterfaces

## 📊 VLAN Breakdown

### Switch 1 (Floor 1)
| VLAN | Department |
|------|------------|
| 10   | Reception  |
| 20   | Store      |
| 30   | Logistics  |

### Switch 2 (Floor 2)
| VLAN | Department |
|------|------------|
| 40   | Finance    |
| 50   | HR         |
| 60   | Sales      |

### Switch 3 (Floor 3)
| VLAN | Department    |
|------|---------------|
| 70   | Administration|
| 80   | IT            |

## ⚙️ Technologies & Concepts Used

- **VLANs** – Logical segmentation for each department
- **Router-on-a-Stick** – Inter-VLAN routing using subinterfaces
- **DHCP** – Dynamic IP address assignment configured per router
- **OSPF** – Dynamic routing protocol enabling communication between all three floors
- **Trunking** – Trunk links configured between routers and switches
- **Cisco Packet Tracer** – Full network design and simulation

## 🛠️ Implementation Highlights

- Designed and built the complete multi-floor topology in Cisco Packet Tracer
- Configured VLANs to isolate traffic per department
- Implemented Router-on-a-Stick with subinterfaces for inter-VLAN routing
- Set up DHCP pools on each router for automatic IP address assignment
- Deployed OSPF to enable dynamic routing between all three floors
- Configured trunk links between routers and switches
- Verified end-to-end connectivity across the entire network

## 📁 Repository Contents

- `[project-file].pkt` – Cisco Packet Tracer project file
- Topology diagrams / screenshots (if included)

## 🚀 How to Open

1. Download and install [Cisco Packet Tracer](https://www.netacad.com/courses/packet-tracer) (free with a Cisco Networking Academy account)
2. Open the `.pkt` file in this repository
3. Use the simulation and command-line tools to explore the configuration

## 🙌 Acknowledgments

Thanks to the **National Telecommunication Institute (NTI)** and my instructor for the hands-on training that made this project possible.

---

## Author

Nour Ahmed Yousef Aly - Computer and Communication Engineering - Cairo University
