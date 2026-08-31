# Secure & Resilient Hospital Network Design

## Project Overview

This project presents the design of a secure, scalable, and resilient network architecture for a fictional healthcare environment.

The network is designed to support multiple hospital departments, a secure data centre, wireless-connected annex facilities, IoT devices, mobile clinical devices, and external healthcare services.

The design focuses on network segmentation, secure communication, high availability, traffic management, monitoring, and protection of sensitive healthcare data.

## Network Architecture

The proposed architecture uses a hybrid wired and wireless network.

Key design components include:

- Next-generation firewall and VPN gateway
- Core switching infrastructure
- Secure data centre
- Department-based VLAN segmentation
- Wireless bridges between hospital facilities
- 4G/5G failover connectivity
- Secure IoT and mobile device connectivity
- Cloud and external healthcare service connectivity

## VLAN & IP Addressing

The internal network uses the private `10.10.0.0/16` address space, with separate VLANs and subnets for different departments.

| Department | VLAN | Subnet |
|---|---:|---|
| Central Control Room | 10 | 10.10.10.0/24 |
| Laboratory Services | 30 | 10.10.30.0/24 |
| Diagnostic Imaging | 40 | 10.10.40.0/24 |
| Sensory Therapy / IoT | 50 | 10.10.50.0/24 |
| Restricted Clinical Area | 60 | 10.10.60.0/24 |
| Labour & Delivery | 70 | 10.10.70.0/24 |
| Data Centre | — | 10.10.20.0/24 |

## Network Technologies

The design incorporates:

- OSPF for internal routing
- BGP for external connectivity
- DHCP and DNS services
- IPsec and TLS 1.3 encryption
- IEEE 802.1X network access control
- SNMPv3 and Syslog monitoring
- Quality of Service (QoS)
- HSRP/VRRP for network redundancy

## Security Design

Security is implemented using multiple layers, including VLAN segmentation, access control, encrypted communications, secure remote access, network monitoring, and the principle of least privilege.

The design also considers VPN security, IoT security, access control, data protection, and the security requirements associated with healthcare environments.

## Resilience & Availability

High availability is supported through:

- Redundant network devices
- Automatic failover
- 4G/5G backup connectivity
- Multiple network paths
- Dual internet connectivity
- Network monitoring and logging
- QoS for critical healthcare traffic
- Local and cloud-based data resilience

## Skills Demonstrated

- Network Architecture Design
- VLAN & Subnet Design
- TCP/IP Networking
- Routing Protocols
- Network Security
- VPN Security
- Wireless Networking
- IoT Networking
- Network Resilience
- Network Monitoring
- Technical Documentation

## Disclaimer

This project was developed for academic and portfolio purposes using a fictional healthcare scenario. It does not represent the network architecture of a real hospital or healthcare organisation.
