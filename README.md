# Basic-Packet-Tracer-Lab

This repository contains a collection of **Cisco Packet Tracer (.pcxt)** labs designed to help learners practice essential networking skills including LAN design, IP addressing, CIDR subnetting, static routing, and basic troubleshooting.

These labs are beginner-friendly and focus on understanding concepts rather than complex device configurations.  
Most labs use **default switch configurations** (no VLAN or STP setup required).

##  Lab Files Overview

| File Name | Description |
|------------|-------------|
| **Subnetting and IP Addressing Lab.pcxt** | Practice dividing a /24 network into subnets using CIDR notation|
| **CIDR Troubleshooting Lab — 192.168.0.0/24.pcxt** | Diagnose and fix IP or gateway issues base on the CIDR table |
| ** Basic IP Addressing and Connectivity Lab.pcxt** |  Configure static routes between networks for inter-LAN communication |
| **Static Routing Troubleshooting Lab.pcxt** | Diagnose and fix IP or gateway issues across subnetted LANs |

##  Objectives

- Understand LAN setup and basic connectivity  
- Apply CIDR subnetting to organize IP addressing  
- Configure and verify static routing between multiple networks  
- Use common troubleshooting commands to identify and resolve issues


| Device | Command | Purpose |
|---------|----------|----------|
| **PC** | `ipconfig` | Check assigned IP address and gateway |
| **PC** | `ping <IP>` | Test connectivity between devices |
| **Router** | `show ip interface brief` | Verify interface IPs and operational status |
| **Router** | `show running-config` | View current router configuration |
| **Router** | `ping <destination>` | Test reachability between subnets |
| **Router** | `ip route <network> <mask> <next-hop>` | Configure static route manually |


##  How to Use

1. Open any `.pcxt` file in **Cisco Packet Tracer (v8.x or newer)**.  
2. Review the topology and assigned IP addresses.  
3. Configure routers (if required) using static routes.  
4. Use `ping` and `show` commands to verify connectivity.  
5. Troubleshoot any failed connections and correct configurations.

##  Learning Outcomes

By completing all four labs, you will learn how to:
- Design and build small LANs using basic devices  
- Implement subnetting with CIDR  
- Configure static routing between multiple networks  
- Diagnose and fix simple connectivity issues  

#  Author
**ONEZID**  

