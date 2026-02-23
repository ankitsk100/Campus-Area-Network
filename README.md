
# Campus Area Network (CAN) — Cisco Packet Tracer Project

This repository contains a complete **Campus Area Network (CAN)** implementation in **Cisco Packet Tracer** with:
- VLAN segmentation per department
- Trunking (802.1Q)
- Router-on-a-Stick inter-VLAN routing
- DHCP per VLAN (router-based)
- WAN connectivity using Serial links
- Dynamic routing using **RIP v2**
- Branch connectivity and Cloud connectivity

---

## Topology

![Campus Topology](docs/topology/topology.png)

---

## VLANs and Subnets

| VLAN | Department      | Subnet            | Gateway (Router Subinterface) |
|------|------------------|-------------------|-------------------------------|
| 10   | ADMIN            | 192.168.1.0/24    | 192.168.1.1                   |
| 20   | HR               | 192.168.2.0/24    | 192.168.2.1                   |
| 30   | FINANCE          | 192.168.3.0/24    | 192.168.3.1                   |
| 40   | BUSINESS         | 192.168.4.0/24    | 192.168.4.1                   |
| 50   | E & C            | 192.168.5.0/24    | 192.168.5.1                   |
| 60   | A & D            | 192.168.6.0/24    | 192.168.6.1                   |
| 70   | LAB              | 192.168.7.0/24    | 192.168.7.1                   |
| 80   | IT-DEPT          | 192.168.8.0/24    | 192.168.8.1                   |
| 90   | BRANCH-LAB       | 192.168.9.0/24    | 192.168.9.1                   |
| 100  | BRANCH-STAFF     | 192.168.10.0/24   | 192.168.10.1                  |

---

## WAN Networks (Serial Links)

| Link                | Subnet         | Device IPs |
|---------------------|----------------|------------|
| Main ↔ Branch       | 10.10.10.0/30  | Main: 10.10.10.1, Branch: 10.10.10.2 |
| Main ↔ Cloud        | 10.10.10.4/30  | Main: 10.10.10.5, Cloud: 10.10.10.6 |
| Cloud ↔ Email Server| 20.0.0.0/30    | Cloud: 20.0.0.1 |

---
