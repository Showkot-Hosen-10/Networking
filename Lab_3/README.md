# 🌍 Router Configuration as Default Gateway

## 🎯 Objectives
- Configure router for inter-network communication  
- Understand role of default gateway  

## 🛠️ Software
- Cisco Packet Tracer

## 📖 Introduction
Routers connect different networks.  
Default gateway allows devices to communicate outside their LAN.

## ⚙️ Procedure
1. PCs, switch, and router were placed  
2. PCs connected to switch  
3. Switch connected to router  
4. IPs assigned to PCs and router  
5. Router IP set as default gateway  
6. Connectivity tested using `ping`  

## 🌐 Network Configuration
| Device | IP Address     | Gateway        |
|--------|---------------|----------------|
| PC1    | 192.168.1.2   | 192.168.1.1    |
| PC2    | 192.168.2.2   | 192.168.2.1    |

Subnet Mask: `255.255.255.0`

## 🖼️ Topology
![Topology](./images/topology.png)

## 📌 Key Insights
- Router enabled inter-network communication  
- Default gateway was essential  
- Without gateway, routing failed  
- Proper interface configuration required  

## 📚 Concept
Basic routing and packet forwarding between multiple networks.
