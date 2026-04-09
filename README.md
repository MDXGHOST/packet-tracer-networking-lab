# Basic Network Lab (Cisco Packet Tracer)

## Overview
This project demonstrates a basic network setup using 4 PCs, 2 switches, and 1 router in Cisco Packet Tracer. The goal was to understand IP addressing, subnetting, and routing between two different networks.

## Network Design
Two separate networks were created:

- Network 1: 192.168.1.0/24  
- Network 2: 192.168.2.0/24  

## IP Addressing

| Device | IP Address | Subnet Mask | Default Gateway |
|--------|------------|-------------|------------------|
| PC1 | 192.168.1.10 | 255.255.255.0 | 192.168.1.1 |
| PC2 | 192.168.1.11 | 255.255.255.0 | 192.168.1.1 |
| PC3 | 192.168.2.10 | 255.255.255.0 | 192.168.2.1 |
| PC4 | 192.168.2.11 | 255.255.255.0 | 192.168.2.1 |

## Router Configuration
The router was configured with two interfaces:
- 192.168.1.1 (Network 1)
- 192.168.2.1 (Network 2)

## Skills Learned
- IP addressing
- Subnetting basics
- Router configuration
- Network connectivity testing using PDU

## Tools Used
- Cisco Packet Tracer
