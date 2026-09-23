# Secure VLAN Network Design for Food Delivery and Logistics Services

## Project Overview

This project demonstrates the design and implementation of a secure VLAN-based enterprise network for a Food Delivery and Logistics organization using Cisco Packet Tracer.

The network separates different departments into dedicated VLANs and enables controlled communication using Router-on-a-Stick inter-VLAN routing.

## VLAN Architecture

| VLAN | Department | Network | Gateway |
|---|---|---|---|
| VLAN 10 | Admin | 192.168.10.0/24 | 192.168.10.1 |
| VLAN 20 | Customer | 192.168.20.0/24 | 192.168.20.1 |
| VLAN 30 | Delivery | 192.168.30.0/24 | 192.168.30.1 |
| VLAN 40 | Kitchen | 192.168.40.0/24 | 192.168.40.1 |
| VLAN 50 | Server | 192.168.50.0/24 | 192.168.50.1 |

## Technologies Used

- Cisco Packet Tracer
- VLAN
- IEEE 802.1Q
- Router-on-a-Stick
- Inter-VLAN Routing
- IPv4
- ICMP
- FTP
- DNS
- HTTP
- Static Routing

## Network Components

- Cisco 2911 Router
- Cisco 2960 Switches
- Admin VLAN
- Customer VLAN
- Delivery VLAN
- Kitchen VLAN
- Server VLAN
- DNS Server
- Web Server
- FTP Server

## Testing

The network was tested using:

- VLAN verification
- Trunk verification
- Intra-VLAN ping
- Inter-VLAN communication
- FTP file transfer
- DNS resolution
- HTTP web access

## Project Files

- `Secure_VLAN_Network.pkt` — Cisco Packet Tracer project
- `screenshots/` — Configuration and testing screenshots
- `documentation/` — Project report and presentation

## How to Run

1. Install Cisco Packet Tracer.
2. Download `Secure_VLAN_Network.pkt`.
3. Open the file in Cisco Packet Tracer.
4. Inspect the VLAN and router configurations.
5. Test connectivity between devices.

## Future Enhancements

- Access Control Lists
- Firewall/IDS integration
- Wireless VLANs
- Cloud integration
- Network redundancy

## Author

**Jayant Kumar**

B.Tech – Computer Science and Engineering  
RV University
