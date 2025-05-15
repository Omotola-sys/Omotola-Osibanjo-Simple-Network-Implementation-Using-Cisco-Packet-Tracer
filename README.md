# Omotola-Osibanjo-Simple-Network-Implementation-Using-Cisco-Packet-Tracer
## Simple Network Implementation Using Cisco Packet Tracer This repository contains a hands-on implementation of a basic network design using Cisco Packet Tracer. The project demonstrates fundamental networking concepts, including device configuration, topology setup, and connectivity testing to simulate a functional network environment.
### Key Highlights:
### 🔌 Network Topology Design – Structured layout with routers, switches, and end devices
### ⚙️ Device Configuration – Setting up IP addressing, subnetting, and basic routing protocols
### 📡 Connectivity Testing – Ping tests, packet analysis, and troubleshooting steps
### 🛠️ Security Considerations – Basic firewall rules and access control settings
### 📊 Simulation & Analysis – Performance evaluation using Cisco Packet Tracer tools
### This project serves as a practical guide for network engineering students, IT professionals, and enthusiasts looking to understand real-world networking scenarios.
## Executive Summary 
### This report outlines the design and implementation of a simple but scalable network infrastructure for ZX Company using Cisco Packet Tracer as a simulation tool. The proposed network architecture addresses ZX Company's immediate connectivity needs while providing room for future growth. The design focuses on security, reliability, and ease of management, incorporating industry best practices to create a solid foundation for the business operations.
## 1. Introduction 
### 1.1 Project Overview 
### ZX Company has requested assistance in designing and implementing a basic network infrastructure to support business operations. This report details in 2 parts:  
### Part 1: A simple network design created in Cisco Packet Tracer that serves as a blueprint for the actual implementation. 
![image](https://github.com/user-attachments/assets/30721b83-c0f1-4752-b02e-2d6f08d8d3bd)
### FIG 1.1- A simple network in Packet Tracer in the Logical Workspace.
![image](https://github.com/user-attachments/assets/bf597320-2115-42d4-8376-7b08aebc2ac4)
### FIG 1.2-IP Addressing Scheme – PC. 
### This shows that an IP address has been assigned to the PC
![image](https://github.com/user-attachments/assets/0024867c-d768-425c-9cb0-2bbc8dc40f96)
### FIG 1.3-IP Addressing Scheme – Server. 
### This shows that an IP address has been assigned to the server.
![image](https://github.com/user-attachments/assets/c9e57287-82be-4431-b030-3e0c69bd78af)
### FIG 1.4- IP Addressing Scheme – PC. 
### Path to assigning an IP address: click on FastEthernetO  IP Configuration  Static  IPv4 Address:192.168.0.1  Subnet Mask: 255.255.255.0
![image](https://github.com/user-attachments/assets/6021c221-3494-4ace-a67b-7f89582db7ea)
### FIG 1.5- Verification of network connectivity to the PC.
### This pathway shows the verification of the IP address that has been entered. 
### Desktop -> Command Prompt -> Click on it -> Type the command “ipconfig”.
### This command displays an IP address, subnet mask, and default gateway assigned to the host or computer.
![image](https://github.com/user-attachments/assets/c14eb8d5-9689-4a00-8f7b-68091e3904f7)
### FIG 1.6- Verification of network connectivity to the server.
### This pathway shows the verification of the IP address that has been entered. 
### Desktop -> Command Prompt -> Click on it -> Type the command “ipconfig”.
### This command displays an IP address, subnet mask, and default gateway assigned to the host or computer.
![image](https://github.com/user-attachments/assets/b2d7efd3-de31-4e11-9ab6-14288830a1c5)
### FIG 1.7- Verification of network connectivity to the server using the ping command 192.168.0.2
### This shows that we have pinged the server using a ping command from the PC and the command sends 4 ICMP packets of 32 bytes of data, 4 packets sent, and 4 packets received. 
### Round Trip Time (RTT) is a Maximum of 6ms and an Average of 2ms, which means that network connectivity works fine.
![image](https://github.com/user-attachments/assets/9c40119f-827c-488d-a603-411cd8f34268)
### FIG 1.8- Sending Simple Test Messages in Realtime Mode.
### The Add Simple PDU tool was used to send a simple one-time ping message, an echo request, to the server. The server responds with an echo reply because all devices have properly configured IP address settings.
## Part 2: Building of the Complete Network Topology.
### 2. Network Design Overview
### 2.1 Network Topology
### The proposed complete network topology utilizes the following components:
### •	A Switch: Connects all network segments and devices
### •	End-User Devices: Additional two Computers and servers
![image](https://github.com/user-attachments/assets/8a5950ac-3249-413b-b2dd-a48f43954a1b)
### FIG 2.1: Complete Network Topology
![image](https://github.com/user-attachments/assets/32e45c6a-feb8-49ef-9409-48ba069ade9d)
### FIG 2.2- Configuring the Firewall on the Server to enable firewall services, block ICMP traffic and allow general IP traffic.
![image](https://github.com/user-attachments/assets/a4017ba2-ba1f-45ac-b31c-68d025018b3a)
### FIG 2.3: Image showing that ICMP traffic is blocked.
### Observe that no replies are received, indicating that ICMP packets are being successfully blocked by the firewall.
![image](https://github.com/user-attachments/assets/bbb075b2-6c4e-4e78-b7f5-b2c9ecfca0e7)
### FIG 2.4: Image shows that the server’s web page loads, demonstrating that HTTP traffic is permitted. It indicates that web traffic is allowed.
