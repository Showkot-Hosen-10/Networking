
---

# 📁 **Lab 6: ACL Configuration & Traffic Filtering**

![Topology](https://www.computernetworkingnotes.com/ccna-study-guide/basic-concepts-and-fundamentals-of-acls.html)
# 🔐 ACL Configuration and Traffic Filtering

## 🎯 Objectives
- Configure ACLs for traffic filtering  
- Control access based on IP conditions  

## 🛠️ Software
- Cisco Packet Tracer  

## 📖 Introduction
ACLs filter traffic by permitting or denying packets. Standard ACLs use source IP, while extended ACLs consider source, destination, and protocol.

## ⚙️ Procedure
1. Network topology was created  
2. IPs and subnet masks assigned  
3. Default gateways configured  
4. Interfaces activated  
5. ACLs created using `access-list`  
6. ACLs applied using `ip access-group`  
7. Connectivity tested using `ping`  

## 🌐 Network Overview
| Network | Address       | Gateway       |
|--------|--------------|--------------|
| A      | 192.168.1.0  | 192.168.1.1  |
| B      | 192.168.2.0  | 192.168.2.1  |
| C      | 192.168.3.0  | 192.168.3.1  |
| D      | 192.168.4.0  | 192.168.4.1  |

Subnet Mask: `255.255.255.0`

## 🖼️ Topology
![Topology](./images/topology.png)

## 🔧 Tasks Summary

### Task 1
Permit only PC9:

access-list 10 permit host 192.168.4.3
access-list 10 deny any

### Task 2
no access-list 10
access-list 20 deny host 192.168.2.3
access-list 20 permit any

### Task 3
access-list 30 permit 192.168.4.0 0.0.0.255
access-list 30 permit host 192.168.3.2
access-list 30 permit host 192.168.2.3
access-list 30 deny any


---
