# Enterprise Multi-Branch Network Infrastructure

A multi-branch enterprise network designed and simulated using **Cisco Packet Tracer**. The project demonstrates network segmentation, inter-branch connectivity, dynamic routing, IP addressing, and essential network services.

## Project Overview

This project simulates an enterprise network connecting four locations:

- Dhaka — Head Office
- Gazipur — Branch Office
- Chattogram — Branch Office
- Sylhet — Branch Office

The network is designed to provide structured communication between departments, centralized services, and connectivity across multiple branches.

## Technologies & Concepts

- Cisco Packet Tracer
- VLAN Configuration
- Inter-VLAN Routing
- OSPF Dynamic Routing (Area 0)
- DHCP Configuration
- DNS Configuration
- HTTP Web Server
- Wireless Network Configuration
- IP Addressing and Subnetting
- Network Management VLAN
- Printer and End-Device Connectivity

## Network Sites

| Location | Network Address |
|---|---|
| Dhaka | `10.10.0.0/16` |
| Gazipur | `10.20.0.0/16` |
| Chattogram | `10.30.0.0/16` |
| Sylhet | `10.40.0.0/16` |

## VLAN Design

The network uses VLANs to separate departments and infrastructure devices.

| VLAN ID | Purpose |
|---|---|
| VLAN 10 | HR |
| VLAN 20 | IT |
| VLAN 30 | Accounts |
| VLAN 40 | Sales |
| VLAN 50 | Admin |
| VLAN 60 | Servers |
| VLAN 70 | WiFi |
| VLAN 80 | Printers |
| VLAN 99 | Network Management |

VLAN availability varies by branch according to the network design.

## Network Services

### DHCP
Provides automatic IP address assignment to supported end devices.

### DNS
Resolves the internal domain name:

`www.enterprise.local`

### Web Server
Hosts an internal website accessible through the enterprise network.

### OSPF
Provides dynamic routing between the network routers using OSPF Area 0.

### Wireless Connectivity
Provides WiFi connectivity for wireless devices in the branch networks.

## Network Verification

The following tests were performed in the Packet Tracer simulation:

- Inter-branch connectivity testing
- PC-to-PC communication
- DHCP address assignment
- OSPF neighbor verification
- Routing table verification
- DNS name resolution
- Internal website access
- WiFi client connectivity
- Printer connectivity

**Internal website:** `http://www.enterprise.local`

## Project Files

The repository includes:

- **Packet Tracer File (`.pkt`):** The simulated network topology and implemented configurations.
- **IP Addressing Plan (`.docx`):** Network addressing documentation and design reference.

## How to Open the Project

1. Install Cisco Packet Tracer.
2. Clone or download this repository.
3. Open the `.pkt` file using Cisco Packet Tracer.
4. Explore the network topology and device configurations.
5. Test connectivity using the end devices and network commands.

## Important Documentation Note

The IP Addressing Plan is a planning reference. Some addressing details and implementation choices may differ from the final Packet Tracer configuration.

For the implemented topology and actual device configurations, refer to the `.pkt` file.

## Learning Objectives

This project helped develop practical understanding of:

- Enterprise network design
- Multi-branch network architecture
- VLAN-based segmentation
- Routing and switching
- DHCP and DNS services
- Network troubleshooting
- Cisco Packet Tracer simulation

---

**Project Type:** Enterprise Network Simulation  
**Platform:** Cisco Packet Tracer  
**Routing Protocol:** OSPF  
**Network Scope:** Four Branch Locations
