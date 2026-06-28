# Cisco School Network

A Cisco Packet Tracer project that simulates a school-wide network with multiple IPv4 subnets, DHCP services, wireless access points, and end-to-end connectivity testing.

---

## 🌐 Network Topology

<img src="images/topology-1.jpg" alt="Network Topology Part 1" width="100%">

<img src="images/topology-2.jpg" alt="Network Topology Part 2" width="100%">

---

## Project Goal

The objective of this project is to design and simulate a reliable school network that supports multiple departments while maintaining organized network segmentation and automatic IP address allocation.

The network includes laboratories, classrooms, teacher rooms, management offices, and a server room connected through a centralized infrastructure.

---

## What Was Implemented

- Multiple IPv4 subnets for different school departments
- DHCP configuration for automatic IP address assignment
- Wireless Access Point configuration
- End-to-end communication testing using ICMP (Ping)
- Centralized school network simulation using Cisco Packet Tracer

---

## Network Segmentation

| Network | Subnet |
|----------|---------|
| Management | 192.168.99.0/24 |
| Laboratory | 192.168.40.0/24 |
| Teacher Room | 192.168.30.0/24 |
| Classroom Right | 192.168.20.0/24 |
| Classroom Left | 192.168.10.0/24 |

---

## Configuration Preview

### DHCP Pool

<img src="images/dhcp-pool.jpg" width="100%">

Configured DHCP pools for each network segment to automate IP address allocation.

---

### Wireless Access Point

<img src="images/access-point-config-1.jpg" width="100%">

<img src="images/access-point-config-2.jpg" width="100%">

Wireless connectivity was configured to allow devices to connect automatically within their designated network.

---

### Connectivity Test

<img src="images/ping-test-1.jpg" width="100%">

<img src="images/ping-test-2.jpg" width="100%">

ICMP Ping tests confirm successful communication between devices across different network segments.

---

## Running the Project

1. Open `School_Wide_Network.pkt` using Cisco Packet Tracer.
2. Wait until the simulation finishes loading.
3. Verify DHCP address assignment.
4. Test connectivity using Ping.
5. Review the wireless and DHCP configurations.

---

## Files

- `School_Wide_Network.pkt` — Cisco Packet Tracer project
- `School_Wide_Network.pdf` — Project documentation
- `images/` — Screenshots used in this repository

---

## Authors

- Aldi Syarif Alhakim
- Alezuna M. Nadhif Pohan
- Muhamad Ihsad Rasyad
