# Project 01: Basic LAN Configuration

## Objective
Build and configure a basic Local Area Network using Cisco Packet Tracer.

## Network Topology
- 1 Cisco 2960 Switch
- 2 PCs
- 1 Console Cable
- Ethernet cables

## IP Addressing

| Device | IP Address | Subnet Mask |
|---|---|---|
| PC0 | 192.168.1.1 | 255.255.255.0 |
| PC1 | 192.168.1.2 | 255.255.255.0 |
| SW1 | 192.168.1.10 | 255.255.255.0 |

## Switch Configuration

- Hostname configuration
- Console password configuration
- Enable secret configuration
- VLAN 1 management IP
- Access port configuration
- Saving configuration

## Commands Used

- enable
- configure terminal
- hostname SW1
- no ip domain-lookup
- enable secret
- service password-encryption
- line console 0
- interface vlan 1
- ip address
- no shutdown
- interface range fastethernet 0/1-2
- switchport mode access
- copy running-config startup-config

## Connectivity Test

Ping test from PC0 to PC1.

## Tools
Cisco Packet Tracer

## Learning Outcomes
Practiced basic switch configuration, console access, IP addressing and LAN connectivity.
