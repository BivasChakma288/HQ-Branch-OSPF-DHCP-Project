# HQ & Branch Network Project — Cisco Packet Tracer

## Project Overview
This project demonstrates an enterprise network connecting a Head Office (HQ) and two branch networks using Cisco Packet Tracer. It focuses on IPv4 addressing, dynamic routing, DHCP, and end-to-end connectivity.

## Topology
- 3 Routers: R-HQ, R-BR1, R-BR2
- 3 Switches
- 6 PCs
- WAN links between routers
- OSPF routing for inter-network communication

## Technologies & Concepts
- IPv4 Addressing and Subnetting
- Cisco IOS CLI Configuration
- OSPF Dynamic Routing
- DHCP Configuration
- LAN and WAN Connectivity
- Network Troubleshooting
- Ping and Routing Table Verification

## IP Addressing Plan

| Network | Network Address | Default Gateway |
|---|---|---|
| HQ LAN | 192.168.10.0/24 | 192.168.10.1 |
| Branch 1 LAN | 192.168.20.0/24 | 192.168.20.1 |
| Branch 2 LAN | 192.168.30.0/24 | 192.168.30.1 |
| HQ–Branch 1 WAN | 10.0.0.0/30 | N/A |
| Branch 1–Branch 2 WAN | 10.0.0.4/30 | N/A |

## Configuration & Verification
- Configured router interfaces and enabled them using `no shutdown`.
- Configured OSPF Area 0 for dynamic routing.
- Configured DHCP pools for LAN clients.
- Verified router interfaces with `show ip interface brief`.
- Verified OSPF neighbors with `show ip ospf neighbor`.
- Checked routing tables using `show ip route`.
- Tested connectivity using `ping`.

## Project Outcome
Successfully completed the lab verification checklist for router interfaces, OSPF neighbor relationships, DHCP address assignment, and connectivity between HQ and branch networks.

## Tools Used
- Cisco Packet Tracer
- Cisco IOS CLI
- GitHub

## Author
Bivas Chakma

*Hands-on networking lab created for CCNA practice and entry-level Network Support / NOC portfolio development.*
