# 🌍 Static Routing Configuration

## 🎯 Objectives
- Implement multiple LANs using static routing  
- Verify end-to-end communication across networks  

## 🛠️ Software
- Cisco Packet Tracer  

## 📖 Introduction
Static routing is a manual routing method where routes are configured using destination network, subnet mask, and next-hop IP. It provides predictable and controlled routing behavior.

## ⚙️ Procedure
1. Routers, switches, and PCs were configured  
2. IP addresses and subnet masks were assigned  
3. Default gateways were set on PCs  
4. Serial links were activated using `no shutdown`  
5. Static routes were configured using `ip route`  
6. Connectivity was verified using `ping`  

## 🌐 Network Overview
| Segment | Network        | Gateway        |
|--------|---------------|----------------|
| LAN1   | 192.168.1.0   | 192.168.1.1    |
| LAN2   | 192.168.2.0   | 192.168.2.1    |
| LAN3   | 192.168.6.0   | 192.168.6.1    |
| LAN4   | 192.168.7.0   | 192.168.7.1    |
| R0–R1  | 192.168.3.0   | Serial Link    |
| R1–R2  | 192.168.4.0   | Serial Link    |
| R2–R3  | 192.168.5.0   | Serial Link    |

Subnet Mask: `255.255.255.0`

## 🖼️ Topology
![Topology](./images/topology.png)

## 📌 Key Insights
- Static routes were manually configured  
- Proper subnetting ensured routing accuracy  
- Default gateways enabled inter-network communication  
- Routing tables were updated manually  
- Predictable routing behavior was observed  

## 📚 Concept
Manual routing using `ip route` for controlled communication.
