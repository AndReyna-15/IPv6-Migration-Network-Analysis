# 🌐 IPv6 Migration & Network Protocol Analysis

### Network Engineering | Wireshark | IPv4/IPv6 | Cybersecurity

## 📌 Project Overview

This academic project evaluates an IPv6 migration strategy for Village Engineering, a realistic manufacturing business scenario presented in the Network Protocol Analysis course at Ivy Tech Community College.

The primary challenge was to develop an IPv6 adoption strategy while maintaining connectivity for six legacy CNC machines that support only IPv4.

I conducted network protocol analysis in a controlled virtual laboratory using Wireshark and developed a phased dual-stack migration proposal designed to minimize operational disruption.

## 🎯 Project Objectives

- Analyze IPv4 and IPv6 network traffic.
- Examine TCP and UDP communication patterns.
- Evaluate dual-stack functionality in a laboratory environment.
- Identify compatibility and security considerations.
- Develop a phased IPv6 migration strategy.
- Preserve IPv4 connectivity for legacy manufacturing equipment.

## 🛠️ Tools & Technologies

- Wireshark
- Virtual Machines
- TCP/IP
- IPv4 and IPv6
- TCP and UDP
- DNS and ICMPv6
- Dual-Stack Networking

## 🔎 Network Analysis

A 15-minute traffic capture was performed in a controlled virtual laboratory to examine normal network communication.

The analysis included:

- Protocol Hierarchy
- TCP Conversations
- IPv6 Conversations
- IPv4 Endpoints
- Wireshark I/O Graphs
- TCP Three-Way Handshake
- TCP Retransmissions and Resets

### Key Findings

- Approximately 61% of observed packets were IPv6 and 39% were IPv4.
- Both IPv4 and IPv6 traffic were present in the laboratory capture.
- TCP sessions showed generally consistent communication patterns.
- No significant abnormal traffic patterns were reported in the baseline analysis.

These findings establish a baseline for the laboratory environment. They do not independently verify the condition of Village Engineering's production network.

## 🔄 Proposed IPv6 Migration Strategy

A five-phase dual-stack migration strategy was developed:

1. **Assessment and Planning:** Inventory devices, analyze traffic, and develop an IPv6 addressing plan.
2. **Pilot Deployment:** Enable dual-stack on selected infrastructure and validate connectivity.
3. **Initial Production Deployment:** Introduce IPv6 gradually while preserving IPv4 connectivity for CNC equipment.
4. **Expanded Deployment:** Extend dual-stack support and validate DNS and IPv6 services.
5. **Optimization:** Review implementation results, update documentation, and plan future equipment upgrades.

The proposed timeline covers 12 months.

## 🔐 Security and Risk Considerations

The project identified several potential risks:

- Production downtime
- Legacy equipment incompatibility
- Network configuration errors
- IPv6 security misconfigurations
- Budget limitations

Recommended mitigations include phased deployment, pilot testing, staff training, updated firewall policies, and continuous monitoring.

## 💡 Skills Demonstrated

- Network traffic analysis
- TCP/IP troubleshooting
- IPv6 migration planning
- Network security assessment
- Risk identification and mitigation
- Technical documentation
- Business continuity planning

## 📚 Project Background

**Institution:** Ivy Tech Community College

**Course:** CSIA 210 — Network Protocol Analysis

**Year:** 2026

**Author:** Andreyna Reyna

### Disclaimer

This project was developed for academic purposes using a realistic business scenario. Packet captures were collected in a controlled laboratory environment. The IPv6 migration plan is a proposal and was not implemented in a production network.
