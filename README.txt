Internal Network Segmentation with OSPF, EIGRP & RIP
📌 Project Overview

This project demonstrates a simulated enterprise network designed for a Networkers Home environment using multiple dynamic routing protocols.
The lab focuses on internal network segmentation, inter-department routing, and secure OSPF deployment in a multi-area topology.

The design reflects a real-world enterprise scenario where different departments operate under different routing domains while maintaining controlled connectivity.

🏗️ Network Architecture

The topology consists of multiple routing domains interconnected through a core router:

OSPF Multi-Area Design

Area 0 (Backbone)

Area 10 (Standard Area)

Area 20 (NSSA Area)

Stub Area

EIGRP Domains

EIGRP AS 111

EIGRP AS 222

Layer 3 Segmentation

Sub-interfaces used for VLAN-style segmentation

Inter-protocol Connectivity

Controlled routing between OSPF and EIGRP domains

🔐 Security Implementation

OSPF Area 0 Authentication

Message-Digest (MD5) Authentication

Key ID: 1

Key String: ccie123

Ensures secure routing updates and prevents unauthorized OSPF adjacency formation

⚙️ Routing Protocols Used
Protocol	Purpose
OSPF	Core enterprise routing with area segmentation
EIGRP	Department-level routing domains
RIP	Legacy routing simulation (for learning & comparison)
🌐 IP Addressing

Structured IPv4 addressing using /24 subnets

Clear separation between departments and routing domains

Backbone and WAN links logically separated from LAN segments

🧪 Lab Objectives

Build a scalable multi-protocol routing environment

Implement OSPF multi-area concepts (Stub & NSSA)

Apply secure routing authentication

Practice Layer 3 segmentation using router sub-interfaces

Understand interoperability between routing protocols

🛠️ Tools & Platform

Cisco IOS / vIOS Routers

Network Simulator (EVE-NG / GNS3 / similar)

GitHub for version control and documentation


