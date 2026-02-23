# 16-Building University Campus Network

# Project Overview
A complete university campus network designed and 
implemented using Cisco Packet Tracer 9.0.

Prepared by: Ugoh Jessica Chinazaekpere

## Campus Structure
- 6 College Buildings
- 3 Multipurpose Halls
- 3 Girls Dormitory Hostels
- 3 Boys Dormitory Hostels
- 1 Administration Building
- **Total: 16 Buildings**

## Network Features
- Hierarchical Core-Distribution-Access Design
- 11 VLANs for network segmentation
- Inter-VLAN routing on Layer-3 Core Switches
- DHCP automatic IP assignment
- DNS and Web Portal (www.university.edu)
- NAT for Internet connectivity
- WiFi Access Points in all buildings
- 4G Cell Tower for cellular coverage
- Redundant Core infrastructure

## Devices Used
- 2x Cisco 3650-24PS (Core Layer-3 Switches)
- 1x Cisco 2911 (Edge Router)
- 16x Cisco 2960-24TT (Distribution Switches)
- 2x Servers (DHCP, DNS, HTTP)
- 1x Cell Tower (4G Coverage)
- Access Points, PCs, Laptops, Smartphones, Tablets

## VLAN Plan
| VLAN | Name | Network |
|------|------|---------|
| 10 | Faculty | 192.168.10.0/24 |
| 20 | Students | 192.168.20.0/24 |
| 30 | Labs | 192.168.30.0/24 |
| 40 | Multipurpose | 192.168.40.0/24 |
| 50 | Guest WiFi | 192.168.50.0/24 |
| 60 | Girls Hostel | 192.168.60.0/24 |
| 70 | Boys Hostel | 192.168.70.0/24 |
| 80 | Administration | 192.168.80.0/24 |
| 90 | Finance/HR | 192.168.90.0/24 |
| 100 | Servers | 192.168.100.0/24 |
| 110 | Management | 10.0.0.0/24 |

## Files Included
- CAMPUS NETWORK JESSICA.pkt — Packet Tracer File
- Jessica_Campus_Network_Configuration.pdf — Full Report
- Topology Screenshot
- Ping Test Screenshot

## Software
Cisco Packet Tracer 9.0

5. Upload screenshots ✅
6. Edit README with project info ✅
7. Share link with lecturer ✅
