# 🔄 RIP Dynamic Routing Implementation

## 🎯 Objectives
- Implement dynamic routing using RIP  
- Observe automatic route learning  

## 🛠️ Software
- Cisco Packet Tracer  

## 📖 Introduction
RIP is a distance-vector routing protocol that uses hop count to determine the best path. Routes are updated automatically through periodic exchanges.

## ⚙️ Procedure
1. Network topology was created  
2. IPs and subnet masks were assigned  
3. Default gateways were configured  
4. Interfaces were activated  
5. RIP was enabled using `router rip`  
6. Networks were added using `network` command  
7. Routing verified using `show ip route`  
8. Connectivity tested using `ping`  

## 🌐 Network Addressing
| Network | Gateway |
|--------|--------|
| 192.168.1.0 | 192.168.1.1 |
| 192.168.2.0 | 192.168.2.1 |
| 192.168.3.0 | 192.168.3.1 |
| 192.168.4.0 | 192.168.4.1 |
| 192.168.5.0 | 192.168.5.1 |
| 192.168.6.0 | 192.168.6.1 |
| 192.168.7.0 | 192.168.7.1 |
| 192.168.8.0 | 192.168.8.1 |
| 192.168.9.0 | 192.168.9.1 |
| 192.168.10.0 | 192.168.10.1 |
| 192.168.11.0 | 192.168.11.1 |
| 192.168.12.0 | 192.168.12.1 |

Subnet Mask: `255.255.255.0`

## 🖼️ Topology
![Topology](./images/topology.png)

## ⚙️ Sample RIP Config
```bash
router rip
version 2
no auto-summary
network 192.168.1.0
network 192.168.2.0
...
